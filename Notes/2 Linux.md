# Linux

##History/История


##General description/Общее описание


##File system/Файловая система


##CMD/Командная строка

Between "user@linux" and '$' the path of current working directory is showing./Между "user@linux:" и '$' показывается текущий путь папки, в которой мы работаем.

user@linux:\~$ (the system waits for the command from the user, now we are located at (the symbol '\~' before '$') the home directory of this user/система ожидает команды от пользователя, сейчас мы находимся  в (символ '\~' перед '$') домашней директории этого пользователя user)

## Fundamental commands/Основные команды

- `ls` — show files and directories in this directory/показать файлы и папки в данной директории, папке (listing, вывести список).

EXAMPLE:
user@linux:\~$ ls (the user enters the command/пользователь вводит команду)
tree notes.txt cat.jpg (system prints the result/система выводит результат)
user@linux:\~$ (system waits for the next command/система ожидает следующей команды)

- `pwd` — show the current path/показать текущий путь (print working directory, вывести директорию, в которой работаем).

EXAMPLE:
user@linux:\~$ pwd
/home/user
user@linux:\~$

- `cd` — change the directory/перейти в определённую папку (change directory, сменить директорию).

EXAMPLE:
user@linux:\~$ cd / (change the directory to root/перемещение в корневую папку)
user@linux:/$ cd home (choice among all the directories in that path)/выбор среди всех папок в этом пути)
user@linux:/home$ cd user
user@linux:/home/user$ cd /home/another_user (change the directory to certain path/переход к папке с конкретным путём)
user@linux:/home/another_user$

- `cat` — print the contain of file/показать, вывести содержание файла (concatenate, конкатенировать).

EXAMPLE:
user@linux:\~$ cat notes.txt
This is my text in this file.
user@linux:\~$

- `echo` — print the next string/вывести следующую строку.

EXAMPLE:
user@linux:\~$ echo Hello
Hello
user@linux:\~$ echo "Hello world!"
Hello world!
user@linux:\~$

## Полезные ссылки
- [Linux handbook](https://linuxhandbook.com/)
- [tryhackme fundamentals part1](https://tryhackme.com/room/linuxfundamentalspart1)
- [tryhackme fundamentals part2](https://tryhackme.com/room/linuxfundamentalspart2)
- [tryhackme fundamentals part3](https://tryhackme.com/room/linuxfundamentalspart3)