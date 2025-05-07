---
## Front matter
title: "Курс на степике"
subtitle: "2 раздел"
author: "Баранов Никита"

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

Пройти второй этап на степике

# Выполнение раздела

## Отчет по второму этапу курса Linux

### Раздел 2.1: Знакомство с сервером

![Для каких задач можно использовать удаленный сервер?](image/1.jpg){#fig:001 width=70%}

![Безопасная передача SSH-ключей](image/2.jpg){#fig:002 width=70%}

### Раздел 2.2: Обмен файлами

![Копирование папки на сервер с содержимым](image/3.jpg){#fig:003 width=70%}

![Устранение проблем с установкой пакетов](image/4.jpg){#fig:004 width=70%}

![Использование Filezilla](image/5.jpg){#fig:005 width=70%}

### Раздел 2.3: Запуск приложений

![Запуск графических приложений на сервере](image/6.jpg){#fig:006 width=70%}

![Способы вызова справочной информации](image/7.jpg){#fig:007 width=70%}

![Работа с форматами файлов](image/8.jpg){#fig:008 width=70%}

## Отчет по заданиям контроля процессов

![Управление фоновыми программами](image/9.jpg){#fig:009 width=70%}

![Отслеживание программ через jobs](image/10.jpg){#fig:010 width=70%}

![Идентификаторы процессов в разных утилитах](image/11.jpg){#fig:011 width=70%}

![Мгновенное завершение остановленного процесса](image/12.jpg){#fig:012 width=70%}

![Действие kill на приостановленный процесс](image/13.jpg){#fig:013 width=70%}

![Использование CPU после остановки](image/14.jpg){#fig:014 width=70%}

![Память после остановки процесса](image/15.jpg){#fig:015 width=70%}

![Память остановленного процесса](image/16.jpg){#fig:016 width=70%}

![Завершение отдельных потоков](image/17.jpg){#fig:017 width=70%}

## Отчет по работе с терминальным менеджером tmux

### Основы работы с tmux

![Запись вывода bowtie в лог-файл](image/19.jpg){#fig:019 width=70%}

![Выбор между bowtie2 и bowtie2-build](image/18.jpg){#fig:018 width=70%}

### Управление вкладками

![Переименование вкладки в tmux](image/24.jpg){#fig:024 width=70%}

![Поведение фонового процесса при закрытии вкладки](image/23.jpg){#fig:023 width=70%}

![Работа tmux при закрытии терминала](image/22.jpg){#fig:022 width=70%}

![Завершение последней вкладки tmux](image/21.jpg){#fig:021 width=70%}

![Переключение между вкладками с приостановленным процессом](image/20.jpg){#fig:020 width=70%}

### Расширенные возможности

![Разделение вкладок в tmux](image/25.jpg){#fig:025 width=70%}

# Выводы

Мы успешно справились со вторым этапом проекта на степике


