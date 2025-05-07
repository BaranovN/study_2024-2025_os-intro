---
## Front matter
title: "Курс на степике"
subtitle: "1 раздел"
author: "Баранов Никита Дмитриевич"

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

Пройти первый раздел на степике

# Выполнение раздела

Выполняем тестовые задания(рис. @fig:001).

![1 вопрос](image/1.jpg){#fig:001 width=70%}

![2 вопрос](image/2.jpg){#fig:002 width=70%}

![Какую операционную систему вы обычно используете?](image/3.jpg){#fig:003 width=70%}

![Что такое виртуальная машина?](image/4.jpg){#fig:004 width=70%}

![Смогли ли вы запустить на своем компьютере Linux?](image/5.jpg){#fig:005 width=70%}

![Создание документа в LibreOffice Writer](image/6.jpg){#fig:006 width=70%}

![Какое расширение имеют установочные пакеты в Linux (Ubuntu)?](image/7.jpg){#fig:007 width=70%}

![Установка плеера VLC и информация об авторах](image/8.jpg){#fig:008 width=70%}

![Для чего можно использовать приложение Update Manager?](image/9.jpg){#fig:009 width=70%}

![Эквивалентные команды ls в терминале](image/10.jpg){#fig:010 width=70%}

![Команды для вывода содержимого определенной директории](image/11.jpg){#fig:011 width=70%}

![Команда для удаления директорий](image/12.jpg){#fig:012 width=70%}

![Поведение терминала и Firefox при команде exit](image/13.jpg){#fig:013 width=70%}

![Эквивалент запуска программы с &](image/14.jpg){#fig:014 width=70%}

![Запуск исполняемого файла и вывод результата](image/15.jpg){#fig:015 width=70%}

![Куда по умолчанию выводится поток ошибок](image/16.jpg){#fig:016 width=70%}

![Команды для записи потока ошибок в файл](image/17.jpg){#fig:017 width=70%}

![Куда деваются сообщения об ошибках в конвейере](image/18.jpg){#fig:018 width=70%}

![Скачивание картинки с указанием пути и имени файла](image/19.jpg){#fig:019 width=70%}

![Опция wget для тихого режима (без вывода сообщений)](image/20.jpg){#fig:020 width=70%}

![Поведение wget при скачивании с фильтрацией по расширению](image/21.jpg){#fig:021 width=70%}

![Различия между архиваторами gzip и zip](image/22.jpg){#fig:022 width=70%}

![Программы-архиваторы, способные создавать архивы из директорий](image/23.jpg){#fig:023 width=70%}

![Опции tar для создания архива .tar.bz2](image/24.jpg){#fig:024 width=70%}

![Поэтический текст с цитатами о любви](image/25.jpg){#fig:025 width=70%}

# Выводы

Мы успешно прошли первый этап курса на степике.

