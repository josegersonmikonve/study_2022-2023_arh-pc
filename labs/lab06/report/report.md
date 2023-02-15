---
## Front matter
title: "Шаблон отчёта по лабораторной работе"
subtitle: "No 06"
author: "НВЕ МАНГЕ ХОСЕ ХЕРСОН МИКО, Группа: НКАбд-03-22 "

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

На шестой лабораторной работе мы научимся использовать “Midnight
commander” и освоим инструкции mov и int языка ассемблера.

# Выполнение лабораторной работы :

1. На этом этапе мы запустили mc.
 
![Ресунек 1](image/6.1.png){ #fig:001 width=95% }
  
2. После этого мы переместились в каталог ~/work/arch-pc. 

![Ресунек 2](image/6.2.png){ #fig:002 width=95% }
 
3. После этого и с помощью клавиши f7 мы создали новую папку lab06.
 
![Ресунек 3](image/6.3.png){ #fig:003 width=95% }
 
4. Используя строку ввода и сенсорную команду, мы создали файл lab6-1.asm.
 
![Ресунек 4](image/6.4.png){ #fig:004 width=95% }
 
5. используя функциональную клавишу F4, мы открыли файл lab6-1.asm. 
 
![Ресунек 5](image/6.5.png){ #fig:005 width=95% }
 
6. Мы скопировали текст программы из листинга 6.1 в файл asm, затем со-
хранили изменения и закрыли файл. 

![Ресунек 6](image/6.6.png){ #fig:006 width=95% }

7. Используя функциональную клавишу F3, мы открыли файл lab6-1.asm для
просмотра. и мы проверили, что файл содержит текст программы.

![Ресунек 7](image/6.7.png){ #fig:007 width=95% }
 
8. Затем мы перевели текст программы lab6-1.asm в объектный файл . Вы-
полнил разметку объектного файла и запустил полученный исполняемый
файл, где программа выводит строку ‘Введите строку:’ и ожидает ввода с
клавиатуры. По запросу, в этот момент мы ввели наше имя и фамилию.

![Ресунек 8](image/6.8.png){ #fig:008 width=95% }
 
9. После этого мы загрузили файл in_out.asm из ТУИСА и с помощью mc мы
смогли переместить файл в правильный каталог.

![Ресунек 9](image/6.9.png){ #fig:009 width=95% }

10. Используя функциональную клавишу f5, мы создали копию файла lab6-
1.asm с именем lab6-2.asm.

![Ресунек 10](image/6.10.png){ #fig:010 width=95% }

11. После этого мы исправляем текст программы в файле lab6-2.asm, используя
подпрограммы из внешнего файла in_out.asm.

![Ресунек 11](image/6.11.png){ #fig:011 width=95% }

12. Затем мы перевели текст программы lab6-2.asm в объектный файл . Вы-
полнил разметку объектного файла и запустил полученный исполняемый
файл.

![Ресунек 12](image/6.12.png){ #fig:012 width=95% }

13. На этом шаге мы меняем функцию sprintLF на функцию sprint Создал
исполняемый файл, и разница заключалась в том, что эта функция изменяет
входные данные на новую строку. 

![Ресунек 13](image/6.13.png){ #fig:013 width=95% }

![Ресунек 14](image/6.14.png){ #fig:014 width=95% }

## Выводы по результатам выполнения заданий :

- В ходе лабораторных работ мы узнали, как использовать midnight
commander, и мы овладели навыками использования инструмента nasm.

# Задание для самостоятельной работы :

## Создание программы без использования внешнего файла :

В этой части мы должны были сделать копию файла lab6-1.asm, а затем мы
должны были создать программу, которая запрашивает ввод строки, затем
позволяет выполнить ввод с клавиатуры и, наконец, отобразить введенную
строку, но без использования внешнего файла in_out.асм.

![Рисунок 15](image/6.15.png){ #fig:015 width=95% }

![Ресунек 16](image/6.16.png){ #fig:016 width=95% }

## создание программы с использованием внешнего файла:

в этой части мы попытались выполнить ту же программу, но с использова-
нием внешнего файла.

![Ресунек 17](image/6.17.png){ #fig:017 width=95% }

![Ресунек 18](image/6.18.png){ #fig:018 width=95% }

## Выводы по результатам выполнения заданий :

- В этой части мы узнали, как создавать и редактировать программы с помощью
подпрограмм и как управлять с помощью языка ассемблера.

# Выводы, согласованные с целью работы :

- На шестой лабораторной работе мы научимся использовать “Midnight
commander” и освоим инструкции mov и int языка ассемблера и мы узнали,
как создавать и редактировать программы с помощью подпрограмм и как
управлять с помощью языка ассемблера.




::: {#refs}
:::



