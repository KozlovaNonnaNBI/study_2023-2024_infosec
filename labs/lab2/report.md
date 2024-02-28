---
## Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "НБИбд-01-22"
author: "Козлова Нонна Юрьевна"

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

Целью данной работы является приобретение практических навыков
установки операционной системы на виртуальную машину, настройки ми-
нимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

1. Открыла VirtualBox (рис. [-@fig:001]).

![Использовала данные команды](image/1.png){#fig:001 width=70%}

2. Настроила VirtualBox по инструкции (рис. [-@fig:002])

![](image/2.png){#fig:002 width=70%}

3. Запустила VirtualBox (рис. [-@fig:003]) 

![Время ожидания 50 минут](image/3.png){#fig:003 width=70%}

4. Вывела версию ядра Linux (рис. [-@fig:004]) 

![Команда Linux version](image/4.png){#fig:004 width=70%}

5. Вывела частоту процессора и модель процессора (рис. [-@fig:005]) 

![Команды Mhz processor и CPU0](image/5.png){#fig:005 width=70%}

6. Вывела объем доступной оперативной памяти (рис. [-@fig:006]) 

![Команда avaiable](image/6.png){#fig:006 width=70%}

7. Вывела на экран тип обнаруженного гипервизора и тип файловой системы корневого раздела.(рис. [-@fig:007]) 

![Команды Hypervisor detected и Filesystem](image/7.png){#fig:007 width=70%}

# Выводы

В ходе лабораторной работы я приобрела практические навыки установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Список литературы{.unnumbered}

::: {#refs}
:::
