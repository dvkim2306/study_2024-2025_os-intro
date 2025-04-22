---
## Front matter
title: "Лабораторная работа №11"
subtitle: "Дисцпилина: Операционные системы"
author: "Денис Вячеславович Ким"

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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

В ходе данной работы мне предстоит познакомиться с редактором emacs, узнать его команды и выполнить задания

# Выполнение лабораторной работы

Открываем emacs: (рис. [-@fig:001]).

![Начальный экран emacs](image/1.jpg){#fig:001 width=70%}

Создаём файл lab11.sh с помощью специальной комбинации: (рис. [-@fig:002]).

![Создание файла](image/2.jpg){#fig:002 width=70%}

Вводим заданный текст: (рис. [-@fig:003]).

![Ввод текста](image/3.jpg){#fig:003 width=70%}

Сохраняем файл: (рис. [-@fig:004]).

![Сохранение файла](image/4.jpg){#fig:004 width=70%}

Проделываем с файлом стандартные процедуры редактирования. Например, вырезаем строку: (рис. [-@fig:005]).

![Вырезание строки](image/5.jpg){#fig:005 width=70%}

Учимся использовать команды по перемещению курсора. Например, перемещаем курсор в начало строки: (рис. [-@fig:006]).

![Перемещение курсора в начало строки](image/6.jpg){#fig:006 width=70%}

Управляем буферами. Выводим список активных буферов на экран: (рис. [-@fig:007]).

![Вывод буферов на экран](image/7.jpg){#fig:007 width=70%}

Делим экран на четыре части: (рис. [-@fig:008]).

![Деление экрана](image/8.jpg){#fig:008 width=70%}

В каждом окне открываем новые файлы и вводим тексты: (рис. [-@fig:009]).

![Ввод текста в новых файлах](image/9.jpg){#fig:009 width=70%}

Переходим в режим поиска и ищем несколько слов: (рис. [-@fig:010]).

![Поиск слов](image/10.jpg){#fig:010 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы я научился работать с редактором emacs.

# Список литературы{.unnumbered}

::: {#refs}
:::
