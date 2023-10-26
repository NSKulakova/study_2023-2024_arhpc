---
## Front matter
title: "Отчет по лабораторной работе №3"
subtitle: "НММбд-02-23"
author: "Кулакова Надежда Сергеевна"

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

Целью работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown

# Задание

Создать отчет с помощью легковесного языка разметки Markdown.

# Теоретическое введение

Markdown — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций.

# Выполнение лабораторной работы

![Откроем терминал и перейдем в каталог arch-pc, обновим локальный репозиторий, введя git pull](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/3.png){#fig:001 width=70%}


![Перейдем в каталог с шаблоном отчета по лабораторной работе №3 и проведем компиляцию шаблона](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/5.png){ #fig:002 width=70% }


![Проверим корректность полученных файлов](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/1.png){ #fig:003 width=70% }


![Удалим полученные файлы с использованием Makefile](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/6.png){ #fig:004 width=70% }


![Откроем файл report.md c помощью gedit](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/7.png){ #fig:005 width=70% }

Заполним отчет в трех форматах и скомпилируем его с использованием Makefile

# Выводы

Процедуры оформления отчетов с помощью легковесного языка разметки Markdown были освоены.

# Список литературы{.unnumbered}

::: {#refs}
:::
