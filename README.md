# Приветствую 👋 
# Меня зовут Антон и я занимаюсь веб-разработкой

## Мои технические навыки, технологии и инструменты:   
###
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
###
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)![Saga](https://img.shields.io/badge/Redux%20saga-86D46B?style=for-the-badge&logo=redux%20saga&logoColor=999999)![Thunk](https://img.shields.io/badge/Redux%20thunk-%231572B6.svg?style=for-the-badge&logo=redux&logoColor=999999)![Observable](https://img.shields.io/badge/Redux%20observable-%23E34F26.svg?style=for-the-badge&logo=redux&logoColor=999999)
###
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
###
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
###
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=white&color=darkorchid&labelColor=darkorchid)![CodeSandbox](https://img.shields.io/badge/Codesandbox-040404?style=for-the-badge&logo=codesandbox&logoColor=DBDBDB)![CodePen](https://img.shields.io/badge/CodePen-white?style=for-the-badge&logo=codepen&logoColor=black)![Repl.it](https://img.shields.io/badge/Repl.it-%230D101E.svg?style=for-the-badge&logo=replit&logoColor=white)


## Мои основные проекты:

## React:

1. Интернет-магазин

     Задачи: 
     >
     > + Создание приложения, всеми основными функциями которого можно пользоваться: 
     >   навигация по экранам, загрузка элементов каталога, выбор категории каталога, поиск товара, добавление товаров в корзину, оформление заказа
     > <!-- > + Внешний вид должен быть аналогичен тому, что представлен в [разметке](https://github.com/Antis85/ra16-diploma/tree/master/html)
     > + Серверный [код](https://github.com/Antis85/ra-diplom-server) предварительно подготовлен, нужно разместить на Heroku
     > + На стороне сервера настроены задержка ответа и генерация ошибок. При загрузке нужно отображать "лоадер", при получении ошибки от сервера - отображать                  сообщение об ошибке -->
     > + По умолчанию поисковое поле скрыто, отображается только иконка поиска в шапке, при первом клике по иконке открывается строка поиска, 
     >   при втором - если был введён текст, то перенаправляет пользователя на страницу каталога, 
     >   с последующим поисковым запросом на сервер (с учетом выбранной категории каталога), если текст не был введен - сворачивает строку поиска
     > + При нажатии на кнопку "Загрузить ещё", в каталоге или на главной странице, данные перезагружаются с учётом строки поиска и выбранной категории каталога
     > + Страница товара открывается при нажатии кнопок "Заказать" в карточках товаров
     > + На странице товара кнопка "В корзину" активируется только тогда, когда есть размеры в наличии и выбран конкретный размер, 
     >   после нажатия на кнопку "В корзину" пользователь перемещается в страницу корзины
     > + Товары, находящиеся в корзине, хранятся локально в localStorage,
     >   после успешного оформления заказа все данные корзины должны быть удалены из state и из localStorage
     > + Виджет корзины в шапке отображает количество позиций в корзине
     > + При вводе несуществующего URL, пользователю должна показываться "страница 404"
     > <!-- > + Для хранения состояния и побочных эффектов использовать ContextAPI/Redux/Thunk/Observable/Saga -->
          
     Технологии: 
     > Html, CSS/Bootstrap, JS, React, React-router, RTK, Web Storage API, Node.js, Koa.js, Fetch API, Yarn, Appveyor, GitHub Pages, Heroku
          
     Репозиторий: https://github.com/Antis85/lad-project     
     Ссылка на страницу: https://antis85.github.io/lad-project
     <!-- Репозиторий: https://github.com/Antis85/ra-diplom -->
     <!-- Ссылка на страницу: https://antis85.github.io/ra-diplom -->     
     ***

<!--2. CRUD сервис (практика с side-эффектами):
    
     > [Redux](https://github.com/Antis85/ra-hw11-api-redux)    
     >
     > [Redux + Thunk](https://github.com/Antis85/ra-hw11-api-thunk)
     >
     > [Redux + Observable](https://github.com/Antis85/ra-hw12-observable-details)
     >   
     > [Redux + Saga](https://github.com/Antis85/ra-hw13-saga-details)
     >     
     > [Ссылка на страницу](https://antis85.github.io/ra-hw13-saga-details)

     ***-->

## Javascript:

1. Приложение-органайзер

     Задачи: 
     >
     > + Разработать приложение-органайзер, предназначенное для хранения информации, поиска, и других сервисов: напоминания, уведомление и интеграция с внешними сервисами, в качестве примеров для реализации взять за основу функциональность Telegram, WhatsApp, Viber, Slack и т.д. 
     > + Обязательные для реализации функции: 
     > 
     > 1. Сохранение в истории ссылок и текстовых сообщений, ссылки должны быть кликабельны и отображаться как ссылки;
     > 
     > 2. Сохранение в истории изображений, видео и аудио (как файлов) - через Drag & Drop и через кнопку загрузки, скачивание файлов на компьютер пользователя;
     > 
     > 3. Ленивая подгрузка: сначала подгружаются последние 10 сообщений, при прокрутке вверх подгружаются следующие 10 и т.д;
     > 
     > + Дополнительно реализованная функциональность: 
     > 
     > 1. Синхронизация - если приложение открыто в нескольких окнах (вкладках), то контент должен быть синхронизирован;
     > 
     > 2. Запись видео и аудио (используя API браузера);
     > 
     > 3. Воспроизведение видео/аудио (используя API браузера);
     > 
     > 4. Отправка геолокации;
     > 
     > 5. Закрепление (pin) сообщений, закреплять можно только одно сообщение (прикрепляется к верхней части страницы):
     > 
     > + Инфраструктура проекта на Npm/Yarn, Webpack, Babel, ESLint, Appveyor
     > + Бэкенд на Node.js + Heroku
     > + Публикация на GitHub Pages
          
     Технологии: 
     > Html, CSS, JS, Node.js, Koa.js, Fetch API, Websocket API, MediaStream Recording API, Navigator Web API, Yarn, Webpack, Webpack DevServer, Babel, ESLint, Appveyor, GitHub Pages, Heroku

     Репозиторий: https://github.com/Antis85/ahj-chaos-organizer
     
     Ссылка на страницу: https://antis85.github.io/ahj-chaos-organizer
     
     ***

2. Браузерная игра

     Задачи: 
     >
     > + Доработать пошаговую игру с уже созданными UI и базовыми классами
     > + Перевести работу проекта на Npm, Babel, Webpack, ESLint, Jest
     > + Дописать оставшуюся функциональность, в соответствии с механикой игры
     > + Разработать автотесты
     > + Публикация на GitHub Pages
          
     Технологии: 
     > Html, CSS, JS, ООП, Web Storage API, Unit-testing, Npm, Webpack, Webpack DevServer, Babel, ESLint, Jest, Appveyor, GitHub Pages
     
     Репозиторий: https://github.com/Antis85/retro-game
     
     Ссылка на страницу: https://antis85.github.io/retro-game
     
     ***

<!--2. TODO лист
     > Репозиторий: https://github.com/Antis85/ahj-dnd-hw1
     > 
     > Ссылка на страницу: https://antis85.github.io/ahj-dnd-hw1

     ***

3. Чат
     > Репозиторий: https://github.com/Antis85/ahj-http-sse-ws-frontend-hw1
     > 
     > Ссылка на страницу: https://antis85.github.io/ahj-http-sse-ws-frontend-hw1

     ***-->



## Верстка:

1. Верстка статичного макета 

     Задачи:
     >    
     > Сверстать макет сайта, 
     > Верстка:
     > + семантичная, 
     > + валидная, 
     > + кроссбраузерная,
     > + pixelperfect,
     > + сетка flexbox,
     > + без сторонних технологий (пре/постпроцессоры, БЭМ, OOCSS, SMACSS, normalize.css, reset.css, bootstrap, autoprefixer и т.д.)
     > 
     > Публикация на GitHub Pages   
     > 
     > Макет:  
     > 
     > <img src=https://github.com/netology-code/html-2-diploma/blob/master/sources/NOEMI_Modern_ru.jpg width=25%></img>

     Технологии: 
     >
     > HTML, CSS
     
     Ссылка на страницу: https://antis85.github.io/noemi_diplom
     
     ***

2. Верстка адаптивного макета

     Задачи:
     >    
     > Сверстать макет сайта для трех групп устройств - десктопные экраны, планшеты и смартфоны,
     > Верстка:
     > + семантичная, 
     > + валидная, 
     > + кроссбраузерная,
     > + pixelperfect,
     > + сетка flexbox,
     > + без сторонних технологий (пре/постпроцессоры, БЭМ, OOCSS, SMACSS, normalize.css, reset.css, bootstrap, autoprefixer и т.д.),   
     > + отображения страницы в промежуточных состояниях 320px-768px-1920px реализовываются с помощью резиновой верстки
     > 
     > Публикация на GitHub Pages
     > 
     > Макеты:  
     >  
     > <img src="https://github.com/Antis85/mq-diploma/blob/master/img/layouts.jpg" width=25%></img>

     Технологии: 
     >
     > HTML, CSS

     Ссылка на страницу: https://antis85.github.io/surface_diplom

##
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=antis85&show_icons=true&hide_title=true&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

![Top Languages Card](https://github-readme-stats.vercel.app/api/top-langs/?username=antis85&layout=compact&hide=shell&theme=dark)

<!--[![Visits Badge](https://badges.pufler.dev/visits/antis85/antis85)](https://badges.pufler.dev)-->
![visitors](https://visitor-badge.glitch.me/badge?page_id=antis85.antis85)
