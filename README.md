[![Build Status](https://semaphoreci.com/api/v1/projects/506a9684-9902-45f0-b8f4-54c6a53fe32c/368286/shields_badge.svg)](https://semaphoreci.com/zoom/generator-icarus)
Icarus (0.1.2)
================

Это фреймфорк HTML-верстки на основе [Yeoman]. Содержит в себе все самое необходимое для работы с версткой. Минификация скриптов/стилей/изображений, умные инклуды, генерация спрайтов, грамотно структурированный Less и многое другое. Для тестирования внутри содержится jsHint и w3c-валидатор верстки.

Более подробное руководство и пример установленного фреймфорка ищите тут: [icarusTemplate]



## Настройка окружения
1. Скачать и установить [nodeJS]
2. В консоли набрать npm i yo -g
3.  В консоли набрать npm i generator-icarus -g

## Установка генератора
1. Создать пустую диекторию для проекта
2. Зайти туда через консоль
3. Набрать  yo icarus
4. Выбрать необходимые зависимости
5. Нажать Enter


Если верстка будет работать на рабочей станции, то в Gruntfile.js
для connect:options:hostname поменять с 0.0.0.0 на localhost,а если на сервере, то ничего не менять



## Todo's

 * Написать тесты
 * Добавить поддержку [AngularJS]
 * Добавить поддержку  [RequireJS]

## Если что-то пошло не так, как надо
Если вы обнаружили ошибку или хотите  добавить пожелание, есть два проверенных способа:

* Завести задачу в [Issues]
* Если вдруг не отвечаю,написать сразу на zoom81@ya.ru



License
----

MIT


**Free Software, Hell Yeah!**
[Issues]: https://github.com/zoom-samara/generator-icarus/issues
[icarusTemplate]: https://github.com/zoom-samara/icarus-template
[Yeoman]: http://yeoman.io/
[nodeJS]:http://nodejs.org
[Twitter Bootstrap]:http://twitter.github.com/bootstrap/
[jQuery]:http://jquery.com
[AngularJS]:http://angularjs.org/
[RequireJS]:http://requirejs.org/
[gruntJS]:http://gruntjs.com/
[normalize.css]: http://necolas.github.io/normalize.css/
[modernizr]:http://modernizr.com/
[font-awesome]: http://fontawesome.io/
