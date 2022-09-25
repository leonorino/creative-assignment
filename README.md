# Творческое задание
*Выполнил Владислав Ястребов*

## Подробности реализации
Задание реализовано в виде [статической страницы](https://github.com/leonorino/creative-assignment/blob/main/page.html) и её [таблицы стилей](https://github.com/leonorino/creative-assignment/blob/main/style.css).

Как только я представил пройденный мной путь в области программирования, я сразу же понял, что его можно разбить на несколько чётких этапов.
Поэтому мне сразу пришло в голову использовать инструмент под названием [fullpage.js](https://alvarotrigo.com/fullPage/).
С другой стороны, хоть немного, но повлияло бы на время загрузки страницы.
Поэтому я отказался от этой идеи и решил реализовать "полноэкранную прокрутку" сам.
Оказалось, что этого эффекта достаточно просто достичь с помощью нескольких строчек css.
За это в моём коде отвечают классы `.fullpage-scrollable` - контейнер, отвечающий за полноэкранную прокрутку и `.section` - один "полный экран", на котором будет отображаться содержимое.

Чтобы дизайн был адаптивным и содержимое можно было прочитать на телефоне, задаю размер шрифтов с помощью `vmax`.

В остальном, для сайта была составлена цветовая палитра из сочетающихся друг с другом цветов.
Упор был сделан на минимализм, ведь на задание отведен достаточно малый промежуток времени.
