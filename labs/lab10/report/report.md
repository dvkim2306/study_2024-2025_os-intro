---
## Front matter
title: "Лабораторная работа №10"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

В ходе данной работы предстоить взаимодействовать с редактором vi, изучить команды и провести манипуляции с файлом.

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

Создайте каталог с именем ~/work/os/lab10 и переходим в него: (рис. [-@fig:001]).

![Создание каталога](image/1.jpg){#fig:001 width=70%}

Вызываем vi и создаем файл hello.sh: (рис. [-@fig:002]).

![Создание файла](image/2.jpg){#fig:002 width=70%}

Нажимаем клавишу i и вводим заданный текст: (рис. [-@fig:003]).

![Ввод текста](image/3.jpg){#fig:003 width=70%}

Нажимаем Escape для перехода в командный режим после завершения ввода текста. Затем нажимаем : для перехода в режим последней строки. Сохраняем текст и выходим: (рис. [-@fig:004]).

![Переход в командный режим](image/4.jpg){#fig:004 width=70%}

Делаем файл неисполняемым: (рис. [-@fig:005]).

![Изменение права доступа к файлу](image/5.jpg){#fig:005 width=70%}

Вызываем vi на редактирование файла: (рис. [-@fig:006]).

![Вызов на исполнение файла](image/6.jpg){#fig:006 width=70%}

Устанавливаем курсор в конец слова HELL второй строки. Переходим в режим вставки и заменяем на HELLO. Нажимаем Escape для возврата в командный режим: (рис. [-@fig:007]).

![Установка курсора в конец слова и редактирование](image/7.jpg){#fig:007 width=70%}

Устанавливаем курсор на четвертую строку и стираем слово LOCAL: (рис. [-@fig:008]).

![Удаление слова](image/8.jpg){#fig:008 width=70%}

Переходим в режим вставки и набираем следующий текст: local, нажимаем Escape для возврата в командный режим: (рис. [-@fig:009]).

![Набор нового текста](image/09.jpg){#fig:009 width=70%}

Устанавливаем курсор на последней строке файла. Вставляем после неё строку, содержащую следующий текст: echo $HELLO. Переходим в командный режим: (рис. [-@fig:010]).

![Вставка текста](image/10.jpg){#fig:010 width=70%}

Удаляем последнюю строку: (рис. [-@fig:011]).

![Удаление строки](image/11.jpg){#fig:011 width=70%}

Отменяем последнюю команду. Записываем изменения и выходим из vi: (рис. [-@fig:012]).

![Отмена команды](image/12.jpg){#fig:012 width=70%}

# Выводы

В ходе выполнения данной лабораторной работы я научился работать с редактором vi.

# Список литературы{.unnumbered}

::: {#refs}
:::
