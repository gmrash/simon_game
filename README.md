# ЗАПУСТИТЬ СЕЙЧАС
 https://airkross.github.io/simon_game_src/

# Игра Simon Says
Используемые технологии: Vue.js

# Правила игры:
• Игровое поле состоят из 4 квадратов / кнопок, каждый из которых производит определенный тон и «загорается» при нажатии.   
• Раунд в игре состоит из устройства, освещающего одну или несколько кнопок в случайном порядке. После чего игрок должен воспроизвести этот порядок, нажимая кнопки.   
• Если игрок успешно воспроизводит последовательность, то они переходят к следующему раунду.  
• Если игрок не воспроизводит последовательность, то игра окончена (уведомление должно отображаться для пользователя).   
• С каждым раундом количество кнопок (последовательность) увеличивается.  

# Функциональность
• При воспроизведении последовательности кнопки / квадрат должны «загореться».  
• Каждая кнопка / квадрат издают уникальный звук во время игры.  

В игре присутствует 3 уровн сложности и 3 режима. Уровни сложности определяются как легкий, нормальный и сложный, детальнее: • Легкий: время между каждой кнопкой в последовательности должно быть 1,5 сек  
• Средний: время между каждой кнопкой в последовательности должно быть 1,0 сек.  
• Сложный: время между каждой кнопкой в последовательности должно быть 0,4 сек.  
Режимы игры:   
• Normal - во время данного режима, для определния последовательности, игрок может использовать как звук так и подсветку кнопок.   
• Sound Only - во время данного режима, для определения последовательности, игрок может использовать только звук.   
• Light Only - во время данного режима, для определения последовательности, игрок может использовать только подсветку кнопок.   
• Free Board - во время данного режима, игроку доступна и подстветка и звук, но отключена функция создающая последовательность для повторения. Данный режим нужен для тренировок.  
  
# Ниже инструкция по разворачиванию проекта:  
1) Скачайте исходники по данной (https://github.com/airkross/simon_game.git) ссылке;  
2) Разархивируйте содержимое архива в папку  
3) В корне проект откройте терминал и выполните команду "npm install"  
4) После загрузки всех пакетных данных, в терменале выполните команду "npm run serve"    
5) Если вам необходимо скомпилировать проект для продакшена, в терминале выполните команду "npm run build"  
