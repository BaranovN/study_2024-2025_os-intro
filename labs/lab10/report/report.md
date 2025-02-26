---
## Front matter
title: "Лабораторная работа № 10"
subtitle: "Текстовой редактор vi"
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

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором vi.
3. Выполнить упражнения, используя команды vi.

# Выполнение лабораторной работы

1. Создайте каталог с именем ~/work/os/lab06.
2. Перейдите во вновь созданный каталог.
3. Вызовите vi и создайте файл hello.sh (рис. @fig:001).
4. Нажмите клавишу i и вводите следующий текст.(рис. @fig:002)
5. Нажмите клавишу Esc для перехода в командный режим после завершения ввода
текста.
6. Нажмите : для перехода в режим последней строки и внизу вашего экрана появится
приглашение в виде двоеточия.
7. Нажмите w (записать) и q (выйти), а затем нажмите клавишу Enter для сохранения
вашего текста и завершения работы.(рис. @fig:003)
8. Сделайте файл исполняемым(рис. @fig:004)

![Создаем каталог и файл hello.sh](image/1.png){#fig:001 width=70%}

![Редактируем файл](image/2.png){#fig:002 width=70%}

![Прописываем :wq чтобы сохранить изменения и выйти](image/3.png){#fig:003 width=70%}

![Делаем файл исполняемым](image/4.png){#fig:004 width=70%}

1. Вызовите vi на редактирование файла(рис. @fig:005)
2. Установите курсор в конец слова HELL второй строки.
3. Перейдите в режим вставки и замените на HELLO. Нажмите Esc для возврата в командный режим.(рис. @fig:006)
4. Установите курсор на четвертую строку и сотрите слово LOCAL.(рис. @fig:007)
5. Перейдите в режим вставки и наберите следующий текст: local, нажмите Esc для
возврата в командный режим.(рис. @fig:008)
6. Установите курсор на последней строке файла. Вставьте после неё строку, содержащую
следующий текст: echo $HELLO.(рис. @fig:009)
7. Нажмите Esc для перехода в командный режим.
8. Удалите последнюю строку.
9. Введите команду отмены изменений u для отмены последней команды.(рис. @fig:010)
10. Введите символ : для перехода в режим последней строки. Запишите произведённые
изменения и выйдите из vi.

![Вызываем ви на редактирование файла](image/5.png){#fig:005 width=70%}

![Заменяем на HELLO](image/6.png){#fig:006 width=70%}

![Стираем LOCAL](image/7.png){#fig:007 width=70%}

![Заменяем на local](image/8.png){#fig:008 width=70%}

![Вставляем строку](image/9.png){#fig:009 width=70%}

![Отменяем последнее действие](image/10.png){#fig:010 width=70%}

# Выводы

Мы познакомились с операционной системой Linux. И получили практические навыки работы с редактором vi, установленным по умолчанию практически во всех дистрибутивах.


