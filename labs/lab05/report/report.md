---
## Front matter
title: "Отчёт по лабораторной работе №5"
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

Целью является получение теоритических и практических навыков по работе с командами NASM mov и int и в midnigt comander.

# Выполнение лабораторной работы

Зайдем в нужную директорию, создадим папку для выполнения лабораторной(рис. [-@fig:001]), там создаем файл lab5-1.asm(рис. [-@fig:002]), открываем этот файл через встроенный в mc редактор(рис. [-@fig:003]).

![создание папки для лабораторной](/C:/Users/79588/OneDrive/Изображения/1е.png){ #fig:001 width=70% }

![создание рабочего файла](/C:/Users/79588/OneDrive/Изображения/2е.png){ #fig:002 width=70% }

![окно редактора файлов mc](/C:/Users/79588/OneDrive/Изображения/3е.png){ #fig:003 width=70% }

Далее напишем код нашей программы и создадим исполняемый файл lab5-1(рис. [-@fig:004]). Так же проверим его работу 

![ассемблирование файла](/C:/Users/79588/OneDrive/Изображения/4е.png){ #fig:004 width=70% }

Скопируем lab5-1.asm, изменим его с использование стороннего файла in_out.asm. (рис. [-@fig:005]) Из полученного lab6-2.asm получим исполныемый файл lab5-2.

![создание рабочего файла с использованием in_out.asm](/C:/Users/79588/OneDrive/Изображения/5е.png){ #fig:005 width=70% }

Если мы изменим в коде программы команду sprintLF на sprint, то вводимые символы будут появляться в той же строке, что и "приглашение".

# Задания для самостоятельного выполнения

Скопируем файл lab5-1.asm и добавим там блок кода, который будет выводить строку из нашего буффера.(рис. [-@fig:006]) Этот файл назовем lab5-3.asm и сделаем из него исполняемый.

![редактирование кода в файле lab5-3](/C:/Users/79588/OneDrive/Изображения/6е.png){ #fig:006 width=70% }

Запустим этот файл(рис. [-@fig:007]). 

![запуск lab5-3](/C:/Users/79588/OneDrive/Изображения/7е.png){ #fig:007 width=70% }

Скопируем файл lab5-2.asm и добавим там блок кода, который будет выводить строку из нашего буффера, но с использованием внешного файла in_out.asm(рис. [-@fig:008])

![код файла lab5-4.asm](/C:/Users/79588/OneDrive/Изображения/8е.png){ #fig:008 width=70% }

![работа файла lab5-4](/C:/Users/79588/OneDrive/Изображения/9е.png){ #fig:009 width=70% }



# Выводы

Были поняты основные механики работы языка ассемблера NASM: создание переменных и помещение данных в регистры.

