####UPD. добавил preloader и улучшил эффект зернистости, надеюсь, работа еще не проверена =)

Киноглушитель протестирован в Chrome на Windows.

#[Перейти на Gh-Pages](https://yuriy-baranov.github.io/homework-3/)

Реализовано:
Эффект черно-белого видео (с помощью шейдера)

Эффект царапин - с помощью наложения видео

Наложение музыки

Так же есть эффект зернистости, он накладывается во фрагментном шейдере после эффекта ч/б: берется 5 случайных пикселей в небольшой окрестности пикселя и его цвет вычисляется как среднее арифметическое их цветов.

Реализованы субтитры.

Из элеметов управления присутствуют play/pause и time-line с перемоткой в любой момент (в том числе на субтитры).

На музыку наложен фильтр, который не пропускает частоты ниже 900 Гц, и к ней добавлен шум, похожий на шум граммофона.