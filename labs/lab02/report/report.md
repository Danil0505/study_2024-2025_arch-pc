---
## Front matter
title: "Лабораторная работа №2"
subtitle: ". Система контроля версий Git"
author: "Демин Даниил"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью работы является освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Выполнение лабораторной работы
Провел первоначальную настройку git, установил имя владельца
репозитория и почту Настроил имя ветки по умолчанию и произвел другие настройки.(рис. [-@fig:001]).

![Конфигурация git](image/1.png){#fig:001 width=70%}

Создал пару ssh-ключей для Github. (рис. [-@fig:002]).

![Создание ключа](image/2.png){#fig:002 width=70%}

Командой cat вывел ключ на экран и скопировал его в буфер обмена (рис. [-@fig:003]).

![Вывод ключа в консоль](image/3.png){#fig:003 width=70%}

Добавил этот ключ на Github (рис. [-@fig:004]).

![Добавление ключа на Github](image/4.png){#fig:004 width=70%}

Создал свой репозиторий с использованием шаблона репозитория https://github.com/yamadharma/course-
directory-student-template (рис. [-@fig:005]).

![Создание репозитория с Github](image/5.png){#fig:005 width=70%}

Создал директорию /work/study/2023-
2024/"Архитектура компьютера". Перешел в нее и скопировал содержимое нового репозитория в эту директорию. (рис. [-@fig:006]).

![Создание репозитория с Github](image/6.png){#fig:006 width=70%}

Перешел в каталог arсh-pc, удалил файл package.json, добавил каталог с названием курса. Выполнил команду для подготовки репозитория. (рис. [-@fig:007]).

![Клонирование репозитория с Github](image/7.png){#fig:007 width=70%}

Сохранил изменения и отправил файлы на сервер Github. (рис. [-@fig:008] и рис. [-@fig:009]).

![Инициализация и сохранение](image/8.png){#fig:008 width=70%}

![Отправка изменений](image/9.png){#fig:009 width=70%}

Проверил, что изменения пришли на Github (рис. [-@fig:010]).

![Репозиторий на Github](image/10.png){#fig:010 width=70%}


# Выполнение самостоятельной работы


# Выводы
Выполнив данную лабораторную работу, я изучил идеологию и применение
средств контроля версий. Приобрел практические навыки по работе с системой git
