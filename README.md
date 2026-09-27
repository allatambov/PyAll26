# PyAll26

## Организационное

Это копия основной [страницы](http://math-info.hse.ru/2026-27/%D0%9F%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5_%D0%B4%D0%BB%D1%8F_%D0%B2%D1%81%D0%B5%D1%85_(%D0%BE%D1%81%D0%BD%D0%BE%D0%B2%D1%8B_%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B_%D1%81_Python)) курса **«Программирование для всех (основы работы с Python)»**, читаемого в 1-2 модулях 2026-2027 учебного года в НИУ ВШЭ.

* Преподаватель: Тамбовцева Алла Андреевна
* Вспомогательный онлайн-курс: [Python как иностранный](https://edu.hse.ru/course/view.php?id=133389) (доступен в SmartLms)

Ниже приведены материалы курса по неделям (содержание курса можно посмотреть в [программе](https://www.hse.ru/edu/courses/1163622945)). 
Иную информацию можно найти на отдельных страницах:

* [оценивание](https://github.com/allatambov/PyAll26/grading.md)
* [программное обеспечение](https://github.com/allatambov/PyAll26/po.md)

## Материалы

### Неделя 0. Подготовка к работе. Настройка рабочего места

Для подготовки к работе на курсе можно ознакомиться с материалами [онлайн-курса](https://edu.hse.ru/course/view.php?id=133389): 

* [Видео. Подготовка рабочего места](https://edu.hse.ru/mod/page/view.php?id=502433)
* [Инструкция по открытию файлов в Jupyter Notebook](https://edu.hse.ru/mod/page/view.php?id=502434)

А также с материалами по работе в Jupyter Notebook и Google Colab:

* Запуск Jupyter без Anaconda Navigator ([инструкция](https://disk.yandex.ru/i/w6yPaRbPcm8yyg))
* Работа в Jupyter Notebook ([видео](https://disk.yandex.ru/i/2NYAqowJjmS2SA)), отличия Google Colab от Jupyter ([видео](https://disk.yandex.ru/i/cGbacX28YtR08g ))

Дополнительные материалы для желающих:

* Набор текста в Jupyter Notebook ([видео](https://disk.yandex.ru/i/bNqLGRjrq_UEjg), [ipynb](https://disk.yandex.ru/d/C1E7Axa0jr4nwQ )), [больше](https://gist.github.com/Jekins/2bf2d0638163f1294637) о Markdown
* LaTeX: [Overleaf](https://www.overleaf.com/), [документация](https://www.overleaf.com/learn), [материалы](https://github.com/allatambov/Latex) по LaTeX

### Неделя 1. Введение в Python. Типы данных. Ввод и вывод

* [Видеозапись](https://disk.yandex.ru/d/yo8JaUC4y-wQbA ) занятий
* Введение в Python: вычисления, переменные, типы данных ([слайды](https://disk.yandex.ru/i/0QkF8Gg82-nQLg))
* Вычисления и импорт библиотек в Python ([ipynb](https://github.com/allatambov/PyAll26/blob/main/01-calculations.ipynb)). Переменные и типы данных ([ipynb](https://github.com/allatambov/PyAll26/blob/main/01-variables-types.ipynb))
* Ввод и вывод, форматирование строк ([ipynb](https://github.com/allatambov/PyAll26/blob/main/01-input-output.ipynb))
* Практикум 1: типы данных, ввод и вывод, форматирование строк ([ipynb](https://github.com/allatambov/PyAll26/blob/main/practice01.ipynb)), решения ([practice01-solved.ipynb](https://github.com/allatambov/PyAll26/blob/main/practice01-solved.ipynb))

Дополнительно для желающих:

* Стандарты оформления кода [PEP8](https://peps.python.org/pep-0008/)
* Документация модулей [decimal](https://docs.python.org/3/library/decimal.html) и [fractions](https://docs.python.org/3/library/fractions.html) для работы с десятичными и обычными дробями соответственно
* Документация [библиотеки](https://www.sympy.org/en/index.html) sympy для символьных вычислений (уравнения, производные, интегралы и проч)
* Интерактивные [виджеты](https://ipywidgets.readthedocs.io/en/stable/examples/Widget%20Basics.html) в Jupyter (альтернатива стандартному вводу и не только)

### Неделя 2. Индексированные структуры данных. Цикл for

* [Видеозапись](https://disk.yandex.ru/d/U4Str6StDw8syQ) занятий
* Структуры данных в Python, изменяемость и неизменяемость ([слайды](https://disk.yandex.ru/i/ho04kC6kHXUzPg))
* Индексированные структуры данных: строки и списки, методы .split() и .join() ([ipynb](https://github.com/allatambov/PyAll26/blob/main/02-str-lists.ipynb))
* Цикл for и функция range() ([ipynb](https://github.com/allatambov/PyAll26/blob/main/02-str-lists.ipynb))
* Практикум 2: списки и цикл for, методы .split() и .join() ([ipynb](https://github.com/allatambov/PyAll26/blob/main/practice02.ipynb)), решения ([practice02-solutions.ipynb](https://github.com/allatambov/PyAll26/blob/main/practice02-solutions.ipynb))

### Лабораторная №1. Условные конструкции и цикл while

*Задачи из лабораторных работ не сдаются на проверку, но их нужно уметь решать, <br>
чтобы успешно проходить дальнейший материал и писать проверочные работы.*

*В проверочную №1 (активность 24.09) выносятся задачи на ввод данных с input() и конструкцию if-else.*

Для выполнения лабораторной работы необходимо изучить формулировку логических выражений,<br>
конструкцию if-else, устройство цикла while и его альтернативу в виде цикла 
for с оператором break.<br>Для этого (на выбор) можно:

* прослушать материал [раздела 2](https://edu.hse.ru/course/view.php?id=133389&section=2) *Условия и логические выражения*, [раздела 3](https://edu.hse.ru/course/view.php?id=133389&section=3) <br>*Цикл с условием* и *Ввод с клавиатуры. Цикл while True* онлайн-курса «Python как иностранный»
* прочитать [конспект](https://github.com/allatambov/PyAll24/blob/main/03-conditions.ipynb) лекции *Логические выражения и условные конструкции* и [конспект](https://github.com/allatambov/PyAll24/blob/main/05-for-range-while.ipynb) лекции про циклы

| | | | |
| --- | --- | --- | --- |
| Задачи | [lab01.ipynb](https://github.com/allatambov/PyAll26/blob/main/lab01.ipynb) | к занятию 24.09 | решения [lab01-solutions.ipynb](https://github.com/allatambov/PyAll26/blob/main/lab01-solutions.ipynb)

### Неделя 3. Кортежи и обработка пар значений. Работа с файлами

* Кортежи, функции zip() и enumerate()
* Практикум 3.1: кортежи и работа с вложенными структурами ([practice03-01.ipynb](https://github.com/allatambov/PyAll26/blob/main/practice03-01.ipynb))
* Практикум 3.2: работа с файлами ([practice03-02.ipynb](https://github.com/allatambov/PyAll26/blob/main/practice03-02.ipynb))

Дополнительно (для желающих):

* Итераторы и последовательности ([обзор](https://www.w3schools.com/python/python_iterators.asp))

### Лабораторная №2. Методы на списках и строках

*Задачи из лабораторных работ не сдаются на проверку, но их нужно уметь решать,*<br>
*чтобы успешно проходить дальнейший материал и писать проверочные работы.*

*В проверочную №2 (активность 01.10) выносятся задачи на методы .append()<br> и .split()
в сочетании с циклом for.*

Для выполнения лабораторной работы необходимо уметь применять методы на списках и строках.

Для этого (один из вариантов на выбор) можно:

* Прослушать материал [темы 5](https://edu.hse.ru/course/view.php?id=133389&section=5) *Методы* онлайн-курса «Python как иностранный».
* Прочитать [конспект](https://github.com/allatambov/PyPerm23/blob/main/str-methods.ipynb) лекции *Методы на строках*, [конспект](https://github.com/allatambov/PyPerm23/blob/main/lists-methods.ipynb) лекции *Методы на списках*.

| | | | |
| --- | --- | --- | --- |
| Задачи | [lab02.ipynb](https://github.com/allatambov/PyAll26/blob/main/lab02.ipynb) | к занятию 01.10 | решения
