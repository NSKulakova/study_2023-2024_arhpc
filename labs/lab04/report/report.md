---
## Front matter
title: "Отчёт по лабораторной работе №4"
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

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.


# Выполнение лабораторной работы


![Создадим каталог для работы с программами на языке ассемблера NASM перейдем в него и создадим текстовый файл с именем hello.asm](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-1.png){#fig:001 width=90%}


![Откроем этот файл с помощью текстового редактора](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-2.png){#fig:002 width=90%}

![Введем в него текст](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-3.png){#fig:003 width=90%}


![Скомпилируем данный текст и проверим, что нужный файл был создан с помощью команды ls.](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-4.png){#fig:004 width=90%}


![Скомпилируем исходный файл hello.asm в obj.o и проверим что файлы были созданы.](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-5.png){#fig:005 width=90%}


![Передадим объектный файл на обработку компоновщику и проверим что исполняемый файл был создан.](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-6.png){#fig:006 width=90%}


![Запустим на выполнение созданный исполняемый файл](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-7.png){#fig:007 width=90%}


# Выполнение заданий для самостоятельной работы

![С помощью команды cp создадим копию файла hello.asm с именем lab4.asm и проверим, что нужный файл был создан с помощью команды ls](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-8.png){#fig:008 width=90%}

![Внесем изменения в текст программы в файле lab4.asm так, чтобы вместо Hello world! на экран выводилась строка с фамилией и именем](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-9.png){#fig:009 width=90%}

![Оттранслируем полученный текст программы lab4.asm в объектный файл, выполним компоновку объектного файла и запустим получившийся исполняемый файл](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-10.png){#fig:010 width=90%}

![Скопируем файлы hello.asm и lab4.asm в локальный репозиторий в папку lab04](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-11.png){#fig:011 width=90%}

![Загрузим файлы на Github.](/afs/.dk.sci.pfu.edu.ru/home/n/s/nskulakova/Изображения/Снимки экрана/4-12.png){#fig:012 width=90%}


# Выводы

Мы освоили процедуры компиляции и сборки программ, написанных на ассемблере NASM.

