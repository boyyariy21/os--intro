---
# Front matter
lang: ru-RU
title: "Отчет по лабороторной работе №3"
subtitle: "Дисциплина: операционные системы"
author: "Фомиченко Илья Владиславович"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Изучить идеологию и применение средств контроля версий.

# Задание

Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.–В качестве отчёта просьба предоставить отчёты в 3 форматах:pdf,docxиmd(вархиве,поскольку он должен содержать скриншоты,Makefile ит.д


# Выполнение лабораторной работы
1.
1) Создаю учётную запись на https://github.com 
![git hub](/home/ilya/work/2020-2021/OS/lab03/1.jpg){ #fig:001 width=70% }
2) Настраиваю систему контроля версий git, как это описано выше c использованием сервера 
![terminal](/home/ilya/work/2020-2021/OS/lab03/2.jpg){ #fig:002 width=70% }
3) Создаю структуру каталога лабораторных работ согласно пункту М.2. 

2. 
1) Создаю репозиторий на GitHub
2) Рабочий каталог буду обозначать как laboratory. 
3) Инициализирую системы git 
4) Создаю заготовку для файла README.md
5) Делаю первый коммит и выкладываем на github
![git hub](/home/ilya/work/2020-2021/OS/lab03/3.jpg){ #fig:003 width=70% }

3.
1) Добавляю файл лицензии 
2) Добавляю шаблон игнорируемых файлов. Просмотриваю список имеющихся шаблонов 
3) Затем скачаем шаблон
4) Добавляю новые файлы 
5) Выполняю коммит
6) Отправляю на github
![git hub](/home/ilya/work/2020-2021/OS/lab03/4.jpg){ #fig:004 width=70% }

4.
1) Инициализирую git-flow
Префикс для ярлыков установим в v
2) Создадаю релиз с версией
3) Записываю версию
4) Заливаю релизную ветку в основную ветку
5) Отправляю данные на github
6) Создаю релиз на github. 
![git hub](/home/ilya/work/2020-2021/OS/lab03/5.jpg){ #fig:005 width=70% }


# Выводы

я изучил идеологию и применение средств контроля версий
