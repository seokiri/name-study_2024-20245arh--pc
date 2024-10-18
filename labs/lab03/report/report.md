0.---
## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "Дисциплина: архитектура компьютера"
author: "Малинина Анастасия Игоревна"

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

Целью данной лабораторной работы является освоение процедуры оформления отчетов с помощью языка разметки Markdown.

# Задание

1.Установка необходимого ПО
2.Заполнение отчета по выполнению лабораторной работы №3 с помощью языка разметки Markdown
3.Здание для самостоятельной работы

# Теоретическое введение

Markdown - язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций. Внутритекстовые формулы делаются аналогично формулам LaTeX. В Markdown вставить изображение в документ можно с помощью непосредственного указания адреса изображения. Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который дается ссылка. Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки кода — это простой способ выделить синтаксис для фрагментов кода.

# Выполнение лабораторной работы

Открываем терминал переходим в каталог курса сформированный при выполнении лабораторной работы (рис. [-@fig:001]).
![переход в каталог курса](image/1.png){#fig:001 width=70%}

Обновляем локальный репозиторий, скачав изменения из удаленного репозитория с помощью команды git pull (рис. [-@fig:002]).
![обновление репозитория](image/2.png){#fig:001 width=70%}


Переходим в каталог с шаблоном отчета по лабораторной работе № 3 и проводдим компиляцию шаблона с использованием Makefile.Сгенерировались файлы report.pdf report.docx.report.md. (рис. [-@fig:003]).
![создание файлов](image/3.png){#fig:001 width=70%}

(рис. [-@fig:004]).
![создание файлов](image/4.png){#fig:001 width=70%}

Проверяем созданные файлы (рис. [-@fig:005]).
![проверка](image/5.png){#fig:001 width=70%}

(рис. [-@fig:005]).
![проверка](image/6.png){#fig:001 width=70%}

(рис. [-@fig:006]).
![проверка](image/7.png){#fig:001 width=70%}

(рис. [-@fig:007]).

Удаляем полученный файлы с использованием Makefile командой make clean (рис. [-@fig:008]).
![проверка](image/8.png){#fig:001 width=70%}

Открываем файл report.md c помощью любого текстового редактора, например gedit (рис. [-@fig:009]).
![проверка](image/9.png){#fig:001 width=70%}

## Задание для самостоятельной работы
Выполнение лабораторной работы №2 в формате markdown

# Выводы

В результате выполнения данной лабораторной работы я освоила процедуры оформления отчетов с помощью легковесного языка разметки Markdown.

# Список литературы{.unnumbered}

::: {#refs}
:::
