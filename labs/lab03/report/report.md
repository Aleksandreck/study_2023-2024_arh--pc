---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "Простейший вариант"
author: "Дмитрий Сергеевич Кулябов"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы

Перехожу в каталог с отчетом по 3 лабораторной работе(рис. @fig:001).

![Использование команды 'сd' для перемещения в файловой системе](image/1.png){#fig:001 width=70%}

Компилирую отчет в нескольких форматах(рис. @fig:002).

![Использование команды 'make' для компиляции](image/2.png){#fig:002 width=70%}

Проверяю результат команды(рис. @fig:003).

![Папка с созданными файлами](image/3.png){#fig:003 width=70%}

Удаляю  созданные файлы (рис. @fig:004).

![Использование команды 'make clean' для удаления](image/4.png){#fig:004 width=70%}

Проверяю результат команды 'make clean' (рис. @fig:005).

![Каталог из которго были удалены файлы](image/5.png){#fig:005 width=70%}

Открываю шаблон для редактирования отчета (рис. @fig:006).

![Использование команды 'gedit'](image/6.png){#fig:006 width=70%}

Внимательно изучаю шаблон(рис. @fig:007).

![Содержимое отчета](image/7.png){#fig:007 width=70%}

# Выводы

В ходе лабораторной работы мной был освоен легковесный язык разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
