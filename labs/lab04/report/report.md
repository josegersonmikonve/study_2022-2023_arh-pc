---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "4"
author: "НВЕ МАНГЕ ХОСЕ ХЕРСОН МИКО , Группа: НКАбд-03-22" 

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
indent: truecd ~/work/study/2022-2023/Архитектура\ компьютера/study_2022-2023_arh-pc/lab03/report/
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

 # Цель работы
В этой лабораторной работе мы рассмотрим более простой способ написа-
ния лабораторного отчета с использованием облегченного языка разметки
Markdown

# Выполнение лабораторной работы

- Прежде всего, мы открываем терминал и переходим в каталог, созданный
во время выполнения третьего круга, когда мы обновляем и загружаем
изменения из удаленного репозитория с помощью команды **git pull**. (рис. [-@fig:fig1])

 ![Ресунек 1](image/1.1.png){ #fig:fig1 width=110%}
 
 \
 \
 
 - Затем мы перешли к каталогу с шаблоном для лабораторного отчета No 4. Затем мы скомпилировали шаблон, используя Makefile с помощью команды make. (рис. [-@fig:fig2])
 
 ![Ресунек 2](image/1.2.png){ #fig:fig2 width=110%}
 
 - После успешной компиляции мы получили два файла report.docx и report.pdf , мы смогли проверить это, используя как команду ls, так и графический файловый менеджер. (рис. [-@fig:fig3]) 
 (рис. [-@fig:fig4])
 
  ![Ресунек 3](image/1.3.png){ #fig:fig3 width=110%}
  
  
  ![Ресунек 4](image/1.4.png){ #fig:fig4 width=110%}
 
  
  
  
- После этого мы удалили созданные файлы с помощью makefile с помощью команды make clean и мы проверили, что файлы действительно были удалены с помощью команды ls. (рис. [-@fig:fig5])

 ![Ресунек 5](image/1.5.png){ #fig:fig5 width=110%}

- После этого мы заполнили отчет report.md и скомпилировал выходные данные. (рис. [-@fig:fig6]) 
 (рис. [-@fig:fig7])
 
  ![Ресунек 6](image/1.6.png){ #fig:fig6 width=110%}
  
  
  ![Ресунек 7](image/1.7.png){ #fig:fig7 width=110%}
  
- Затем нам нужно было поместить созданные файлы в ваш удаленный репо-
зиторий, поэтому мы перешли в локальный репозиторий и ввели следую-
щие команды, как указано в 
  


# Задание для самостоятельной работы

- В этой части работы первое, что нам нужно сделать, это перейти в правиль-
ный каталог, который после этого был выделен для третьей лаборатории, и
с помощью команды gedit мы запустили файл report.md итак, мы можем
приступить к подаче третьего отчета.  (рис. [-@fig:fig8)  (рис. [-@fig:fig9)
 
 
 ![Ресунек 8](image/1.8.png){ #fig:fig8 width=110%}
 
 
 ![Ресунек 9](image/1.9.png){ #fig:fig9 width=110%}

- После этого мы заполнили отчет по результатам работы, проделанной в
третьей лаборатории.
- после заполнения отчета мы составили report.md используя makefile, ко-
торый предоставляет отчет в двух разных форматах.(рис. [-@fig:fig10)

![Ресунек 10](image/1.10.png){ #fig:fig10 width=110%}


- После этого мы перенесли все созданные файлы в удаленный репозиторий. 
 




# Выполнение лабораторной работы

Описываются проведённые действия, в качестве иллюстрации даётся ссылка на иллюстрацию (рис. [-@fig:001])




# Выводы

- в этих упражнениях мы применили все навыки, полученные в теорети-
ческой части, и попытались заполнить отчет для третьей лабораторной
работы, используя markdown, и переместили файлы в удаленное хранили-
ще в соответствующем каталоге.




