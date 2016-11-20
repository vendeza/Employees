# README #
Содержит клиентскую часть для разработки сервисов . Клиентская часть включает в себя общее стилевое оформление а также общие интерактивные компоненты.

### Компоненты и стили ###
* Общая типографика
* Верхнее меню
* Элементы управления форм (метки, поля ввода, автокомплиты, чекбоксы и т.д.)
* Таблица
* Кнопки
* Вкладки
* Хлебные крошки
* Пейджинг
* Модальные окна (только стили, без интерактивности)

### Где посмотреть примеры? ###
После запуска локального сервера (см. ниже), тестовая страница доступна по адресу [http://localhost:9000/pages/styleguide.html](http://localhost:9000/pages/styleguide.html)

На тестовой странице описывается **примерное** использование компонентов, любые пожелания по изменению и доработке можно обсудить и внедрить.

### Разработка ###
1. Для удобной разработки предлагается использовать [node.js](http://nodejs.org/) и систему сборки [gulp](http://gulpjs.com/).
1. Основные таски для gulp:
    1. run - запускает локальный livereload сервер для статики, watcher для слежения за изменениями в файлах
    1. release - выполняет сборку библиотеки, результат кладется в директорию release/<версия из package.json>