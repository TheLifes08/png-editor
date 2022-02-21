# PNG Editor v1.0.0

Зависимости:

1. Фреймворк Qt 5.14.2
	Установка: https://wiki.qt.io/Install_Qt_5_on_Ubuntu
2. Библиотека libpng
	Установка: sudo apt-get install libpng-dev

Запуск программы:

1. Запустите программу Qt Creator (идет в комплекте с Qt)
2. Откройте вкладку 'Начало'. Во вкладке 'Проекты' нажмите 'Открыть' и выберите .pro файл (файл проекта, находящийся в папке src)
3. Выполните сборку проекта и запустите программу

Скриншоты примеров работы программы находятся в папке images_test
Скриншоты примеров обработки ошибок программой находятся в папке images_error
Картинки, на которых я запускаю программу находятся в папке images

Инструменты программы:

1. Рисование квадрата. Для начала выберите инструмент "Drawing a square", нажав на соответствующую кнопку в панели интсрументов. Параметры можно настроить в той же панели инструментов: первый цвет отвечает за цвет границы, второй цвет отвечает за цвет заливки, line width - толщина линий квадрата, square side - размер стороны квадрата, выбрать тип заливки можно при помощи кнопки "Square filling" на пенели инструментов. Далее выберите место расположение левого верхнего угла квадрата на изображении, нажав на это место левой кнопкой мыши. Следует отметить, что квадрат будет размером СторонаКвадрата на СторонаКвадрата пикселей, при этом изменение параметра толщины линий квадрата не изменит итоговые размеры квадрата (увеличение толщины линий происходит вовнутрь). 
2. Перестановка 4 частей изображения в выбранной области. Для начала выберите инструмент "Exchange 4 parts of the selected area", нажав на соответствующую кнопку в панели инструментов. Выбрать метод перестановки частей можно при помощи кнопки "Exchanging parts method" на пенели инструментов. Далее выберите область, которую нужно поделить на части и поменять их местами. Для этого зажмите левую кнопку мыши в одном из углов этой области, далее не отпуская клавишу наведите на противоположный угол области, после отпустите кнопку (работает так же, как выделение в различных ОС). Следует отметить, что в случае выбора области, которую невозможно поделить на 4 равные части, правая или нижняя граница области могут сдвинутся на 1 пиксель.
3. Замена самого часто встречающегося цвета. Для начала выберите цвет замены, это можно сделать на панели инструментов - цвет 1. Далее выполните замену цвета, нажав на кнопку "Replace a common color" в панели инструментов. Следует отметить, что программа считает разными цвета с одинаковыми R, G, B, но различными A значениями.
4. Инверсия цвета в выбранной области. Для начала выберите инструмент "Color inversion in the selected area", нажав на соответствующую кнопку в панели инструментов. Далее выберите область, в которой нужно выполнить инверсию цвета. Для этого зажмите левую кнопку мыши в одном из углов этой области, далее не отпуская клавишу наведите на противоположный угол области, после отпустите кнопку (работает так же, как выделение в различных ОС). Следует отметить, что при инверсии цвета его A значение не меняется.
