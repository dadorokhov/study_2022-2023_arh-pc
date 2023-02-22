---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown."
author: "Дорохов Данила Антонович"

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
Освоение процедуры оформления отчетов с помощью легковесного
языка разметки Markdown.

# Выполнение лабораторной работы

1. Откроем терминал:

![ Терминал ](1.png){ #fig:001 width=90% }

2. Перейдем в каталог
курса сформированного при выполнении лабораторной работы No3 при помощи
команды cd:

![ Переход в каталог ](2.png){ #fig:002 width=90% }

Обновим локальный репозиторий, скачав изменения из удаленного репозитория с
помощью команды git pull:

![ Обновим репозиторий ](3.png){ #fig:003 width=90% }

3. Перейдем в каталог с шаблоном отчета по лабораторной работе No4 при помощи
команды cd:

![ переход в каталог ](4.png){ #fig:004 width=90% }

4. Проведем компиляцию шаблона с использованием Makefile. Для этого введем
команду make, в моем случае она не заработала по непонятным причинам, не
прогрузилась до конца, хотя ждал очень большое количество времени.
Проверим появившиеся файлы:

![ Проверим файлы ](5.png){ #fig:005 width=90% }

5. Удалим полученный файлы с использованием Makefile.Для этого введем команду
make clean:

6. Откроем файл report.md c помощью любого текстового редактора, в нашем случае
gedit:

![Открытие файла](6.png){ #fig:006 width=90% }

8. Заполним отчет и скомпилируем его, используя Makefile. Также проверим
корректность полученных файлов.

![заполним отчет](7.png){ #fig:007 width=90% }

9.  Загрузим файлы на github и проверим их на сайте.

![Загрузим файлы на github](8.png){ #fig:008 width=90% }

![Загрузим файлы на github](9.png){ #fig:009 width=90% }

![Загрузим файлы на github](10.png){ #fig:010 width=90% }

# Вывод

Я освоил процедуры оформления отчетов с помощью легковесного языка
разметки Markdown.


