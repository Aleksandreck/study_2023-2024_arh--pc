---
## Front matter
title: "Лабораторная работе №5"
subtitle: "Архитектура компьютера"
author: "Иванов А.О. НММбд-02-23"

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

Приобретение практических навыков работы в Midnight Commander. Освоение инструкций
языка ассемблера mov и int.
                    

# Выполнение лабораторной работы

Открытие Midnight Commander  с помощью команды mc (рис. @fig:001).

![Использование комманды mc](image/1.png){#fig:001 width=70%}

Открытие каталога lab05 и создание файла lab5-1.asm (рис. @fig:002).

![Использование комманды touch](image/22.png){#fig:002 width=70%}

Выполнение компановки первого кода и его запуск (рис. @fig:003).

![запуск кода](image/3.png){#fig:003 width=70%}

Перемещение внешнего файла в рбочую папку (рис. @fig:004).

![результат переноса файла в окне Midnight Commander](image/44.png){#fig:004 width=70%} 

В ходе сравнения работы двух кодов: первого и второго отредактированного я заметил отличия в переносе строки   (рис. @fig:005).

![Вывод результатов](image/55.png){#fig:005 width=70%}

# Самостоятельная работа

Редактирование первого кода под требуемые задачи, вывод результатов   (рис. @fig:006).

![Результат работы первой программы](image/123.png){#fig:006 width=70%}

Редактирование второго кода под требуемые задачи, вывод результатов   (рис. @fig:007).

![Результат работы второй программы](image/009.png){#fig:007 width=70%}

# Выводы

В ходе выполнения лабораторной работы были приобретены  практические навыки работы в Midnight Commander и освоены инструкции яхыка ассемблера mov и int

# Список литературы{.unnumbered}

::: {#refs}
:::
