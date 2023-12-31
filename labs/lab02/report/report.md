---
## Front matter
title: "ЛР2_Кулакова_отчёт"
subtitle: "Простейший вариант"
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

Ознакомиться с принципами работы средств контроля версий. Настроить git
для начала работы. Используя git, создать рабочее пространство и
репозиторий курса, после чего загрузить файлы на github.

# Результаты выполнения лабораторной работы

Рис.1 Создаём учётную запись на сайте github.

![](image/1.jpg){#fig:001 width=70%}

Рис.2 Укажем имя и e-mail владельца репозитория.

![](image/2.jpg){#fig:001 width=70%}

Рис.3 Настроим utf-8 в выводе сообщений git.

![](image/3.jpg){#fig:001 width=70%}

Рис.4 Зададим имя “мастер” для начальной ветки.

![](image/4.jpg){#fig:001 width=70%}

Рис.5 Настроим параметры autocrlf и safecrlf.

![](image/5.jpg){#fig:001 width=70%}

Рис.6 Сгенерируем пару ключей (приватный и открытый).

![](image/6.jpg){#fig:001 width=70%}

Рис.7 Скопируем из локальной консоли ключ в буфер обмена.

![](image/7.jpg){#fig:001 width=70%}

Рис.8 Создаем SSH ключ.

![](image/8.jpg){#fig:001 width=70%}

Рис.9 Создадим каталог для предмета «Архитектура компьютера».

![](image/9.jpg){#fig:001 width=70%}

Рис.10 и Рис.11 Создадим репозиторий курса на основе шаблона через web-интерфейс github.
![](image/10.jpg){#fig:001 width=70%}

![](image/11.jpg){#fig:001 width=70%}

Рис.12 Перейдём в каталог курса и клонируем созданный репозиторий.

![](image/12.jpg){#fig:001 width=70%}

Рис.13 Перейдём в каталог курса, удалив лишние файлы, и создадим необходимые
каталоги.

![](image/13.jpg){#fig:001 width=70%}

Рис.14 Введём команды git add . и git commit -am.

![](image/14.jpg){#fig:001 width=70%}

Рис.15 Введём команду git push и отправим файлы на сервер.

![](image/15.jpg){#fig:001 width=70%}

Рис.16 Проверим правильность создания иерархии рабочего пространства на
странице github.

![](image/16.jpg){#fig:001 width=70%}



# Выводы

По итогам работы идеология и применение средств контроля версий изучены.
После базовой настройки git создали иерархию рабочего пространства в
локальном репозитории и на странице github.

