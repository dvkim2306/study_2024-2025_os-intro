---
## Front matter
title: "Отчет о прохождении 1 этапа внешнего курса"
subtitle: "Введение"
author: "Ким Денис Вячеславович"

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

Ознакомиться с функционалом операционной системы Linux.

# Задание

Просмотреть видео и на основе полученной информации пройти тестовые задания.

# Теоретическое введение

Линукс - в части случаев GNU/Linux — семейство Unix-подобных операционных систем на базе ядра Linux, включающих тот или иной набор утилит и программ проекта GNU, и, возможно, другие компоненты. Как и ядро Linux, системы на его основе, как правило, создаются и распространяются в соответствии с моделью разработки свободного и открытого программного обеспечения. Linux-системы распространяются в основном бесплатно в виде различных дистрибутивов — в форме, готовой для установки и удобной для сопровождения и обновлений, — и имеющих свой набор системных и прикладных компонентов, как свободных, так и проприетарных. 

# Выполнение лабораторной работы

1 Этап: (рис. @fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006, @fig:007, @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015, @fig:016, @fig:017, @fig:018, @fig:019, @fig:020, @fig:021, @fig:022, @fig:023, @fig:024, @fig:025, @fig:026, @fig:027, @fig:028, @fig:029, @fig:030, @fig:031, @fig:032).

![Задание 1](image/1.png){#fig:001 width=70%}

Курс действительно называется "Введение в Linux", поэтому с этим вопросом проблем не возникло.

![Задание 2](image/2.png){#fig:002 width=70%}

Прочитав критерии прохождения курса, отмечаем необходимые утверждения.

![Задание 3](image/3.png){#fig:003 width=70%}

Стандартная операционная система, предлагаемая большей частью магазинов - windows, именно она стоит у меня на основном компьютере.

![Задание 4](image/4.png){#fig:004 width=70%}

На свой компьютер мы устанавливали специальную программу VirtualBox, которая нужна для подключения одной операционной на другой.

![Задание 5](image/5.png){#fig:005 width=70%}

Да, моя виртуальная машина хорошо работает, и у меня получилось запустить с неё Линукс, но в последнее время я чаще использую ноутбук, на котором Линукс стоит как основная операционная система.

![Задание 6](image/6.png){#fig:006 width=70%}

Создаём документ, и перед сохранением выбираем нужный формат, а после прикрепляем к курсу. Прикрепленный файл видно на скриншоте.

![Задание 7](image/7.png){#fig:007 width=70%}

deb — формат пакетов операционных систем проекта Debian. Используется также их производными, такими как Ubuntu, Knoppix и другими.

![Задание 8](image/8.png){#fig:008 width=70%}

![Задание 8](image/9.png){#fig:009 width=70%}

Установив программу медиапроигрывателя видим, кто автор программы и записываем первую фамилию.

![Задание 9](image/10.png){#fig:010 width=70%}

Менеджер обновлений — это программа для обновления установленного программного обеспечения в дистрибутивах ОС Linux, основанных на Debian или использующих систему управления пакетами APT. Менеджер обновлений устанавливает обновления безопасности или просто улучшающие функциональность программы.

![Задание 10](image/11.png){#fig:011 width=70%}

Ассоль - героиня литературного произведения, а термин - это определение.

![Задание 11](image/12.png){#fig:012 width=70%}

Интерфейс командной строки Linux является регистрозависимым.

![Задание 12](image/13.png){#fig:013 width=70%}

Интерфейс командной строки Linux является регистрозависимым, поэтому не подходит вариант, где буква А - маленькая(строчная).

![Задание 13](image/14.png){#fig:014 width=70%}

Прописываем полный путь до директории Downloads, так как на данный момент находимся в другой директории.

![Задание 14](image/15.png){#fig:015 width=70%}

rm -r удаление директории и рекуррентное удаление файлов, находящихся в ней.

![Задание 15](image/16.png){#fig:016 width=70%}

Проверяем эмпирическим путём, что видно в ходе скринкаста.

![Задание 16](image/17.png){#fig:017 width=70%}

Это запуск программы в фоновом режиме.

![Задание 17](image/18.png){#fig:018 width=70%}

![Задание 17](image/19.png){#fig:019 width=70%}

Здесь видно выполнение команды.

![Задание 18](image/20.png){#fig:020 width=70%}

Автоматически поток ошибок выводится на экран - это видно, например, в ходе выполненных лабораторных. В файл будет поток выводиться, если его перенаправить.

![Задание 19](image/21.png){#fig:021 width=70%}

< file — использовать файл как источник данных для стандартного потока ввода.

> file — направить стандартный поток вывода в файл. Если файл не существует, он будет создан, если существует — перезаписан сверху.

2> file — направить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существует — перезаписан сверху.

>>file — направить стандартный поток вывода в файл. Если файл не существует, он будет создан, если существует — данные будут дописаны к нему в конец.

2>>file — направить стандартный поток ошибок в файл. Если файл не существует, он будет создан, если существует — данные будут дописаны к нему в конец.

&>file или >&file — направить стандартный поток вывода и стандартный поток ошибок в файл. Другая форма записи: >file 2>&1.

![Задание 20](image/23.png){#fig:022 width=70%}

1. cat names.txt | ./interacter.py | less = вывод на экран

2. cat names.txt | ./interacter.py 2>err.txt | less = вывод ошибки в err.txt

![Задание 21](image/24.png){#fig:023 width=70%}

Команда wget -P /home/alex/Pictures http://example.com/example.jpg  скачивает файл и даже размещает его, назвав example.jpg, в папке /home/alex/Pictures. Но после этих манипуляций срабатывает часть ключа -O 1.jpg и только что скачаный example.jpg конвертируется в 1.jpg и размещается в текущей директории, в которой мы находимся, потому что путь файла уже не указан, указано только название - 1.jpg.

![Задание 22](image/25.png){#fig:024 width=70%}

-q
--quiet
    Turn off Wget's output. 

![Задание 23](image/26.png){#fig:025 width=70%}

4.2 Типы файлов

При загрузке материалов из Интернета вы часто захотите ограничить поиск только определенными типами файлов. Например, если вы заинтересованы в загрузке GIF-файлов, вы не будете рады получить кучу документов PostScript, и наоборот.

Wget предлагает две опции для решения этой проблемы. В описании каждой опции перечислены краткое имя, длинное имя и эквивалентная команда в .wgetrc.

'-A acclist'
'--accept acclist'
'accept = acclist'
'--accept-regex urlregex'
'accept-regex = urlregex'

    Аргумент опции '--accept' представляет собой список суффиксов или шаблонов файлов, которые Wget будет загружать при рекурсивном получении. Суффикс - это конечная часть файла, состоящая из "обычных" букв, например, 'gif' или '.jpg'. Шаблон совпадения содержит подстановочные знаки типа shell, например, 'books*'.

    Таким образом, указав 'wget -A gif,jpg', Wget загрузит только файлы, заканчивающиеся на 'gif' или 'jpg', то есть GIF и JPEG. С другой стороны, 'wget -A "zelazny*196[0-9]*" загрузит только файлы, начинающиеся с 'zelazny' и содержащие в себе числа от 1960 до 1969. Описание того, как работает сопоставление шаблонов, можно найти в руководстве к вашей оболочке.

![Задание 24](image/27.png){#fig:026 width=70%}

![Задание 25](image/28.png){#fig:027 width=70%}

gzip (сокращение от GNU Zip) — утилита сжатия и восстановления (декомпрессии) файлов, использующая алгоритм Deflate.

![Задание 26](image/29.png){#fig:028 width=70%}

c - архиватор

j - указатель на тип архиватора bzip 

f - потому что создаем архив в файловой системе

![Задание 27](image/30.png){#fig:029 width=70%}

`?` = один символ

`alexey` = маленькая буква

И файл должен быть `jpeg`, а не `jpg`

![Задание 28](image/31.png){#fig:030 width=70%}

Регистр - маленькая буква, слово - `world`, а не `word`

![Задание 29](image/32.png){#fig:031 width=70%}

![Задание 29](image/33.png){#fig:032 width=70%}

`grep -r "love" ~/Shakespeare/ > 1_m.txt`

# Выводы

Мы просмотрели курс и освежили в памяти навыки работы с архивами, скачивание файлов, команды grep и тп.

# Список литературы{.unnumbered}

1. Введение в Linux

::: {#refs}
:::
