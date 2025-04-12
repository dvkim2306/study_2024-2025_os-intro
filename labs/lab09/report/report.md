---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Дисциплина: Операционные системы"
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

 Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Задание

В ходе данной работы мне предстоит познакомиться с командной оболочкой Midnight Commander

# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

Изучаем информацию о mc, вызвав в командной строке man mc: (рис. [-@fig:001]).

![Вызов man mc](image/1.jpg){#fig:001 width=70%}

Запускаем из командной строки mc, изучаем его структуру и меню: (рис. [-@fig:002]).

![Запуск mc](image/2.jpg){#fig:002 width=70%}

Выполняем несколько операций в mc, используя управляющие клавиши: (рис. [-@fig:003]).

![Копирование строки](image/3.jpg){#fig:003 width=70%}

Выполняем основные команды меню левой панели. Информация о файле дана достаточно полно: (рис. [-@fig:004]).

![Изучение информации о файле](image/4.jpg){#fig:004 width=70%}

Выполняем несколько операций с помощью подменю Файл: (рис. [-@fig:005]).

![Просмотр файла](image/5.jpg){#fig:005 width=70%}

Выполняем несколько операций с помощью подменю Команда: (рис. [-@fig:006]).

![Поиск файла в файловой системе](image/6.jpg){#fig:006 width=70%}

Вызываем подменю Настройки: (рис. [-@fig:007]).

![Изменение внешнего вида](image/7.jpg){#fig:007 width=70%}

Создаем текстовый файл text.txt: (рис. [-@fig:008]).

![Создание текстового файла](image/8.jpg){#fig:008 width=70%}

Открываем его с помощью mc и вставляем в него текст: (рис. [-@fig:009]).

![Открытие файла](image/9.jpg){#fig:009 width=70%}

Проделываем с текстом манипуляции. Удаляем строчку текста: (рис. [-@fig:010]).

![Удаление строки](image/10.jpg){#fig:010 width=70%}

ВЫделяем фрагмент и переносим его на следующую строку: (рис. [-@fig:011]).

![Перенос фрагмента](image/11.jpg){#fig:0011 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы научился работать с командной оболочкой Midnight Commander.

# Список литературы{.unnumbered}

::: {#refs}
:::
