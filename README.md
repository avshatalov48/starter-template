Это стартовый проект, который помогает ускорить начало работы над шаблоном сайта.
---
##### Описание:
* Для сборки используется gulp
* Для подключения сторонних биботек используется bower
* Имеется поддержка BrowserSync для PHP, необходим локально установленный PHP
* Autoprefixer
* Минификация JS и CSS
* Поддержка SASS

##### Пример использования:
* `gulp` - запускет задачу сборки по-умолчанию
* `gulp watch` - дополнительно запускает слежение за изменениями файлов
* `gulp life` - запускает watch и BrowserSync для автоматической перезагрузки страницы при изменениях
* `gulp live:html` - то же, что и выше, только без PHP
