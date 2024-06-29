Тест 3

1. Каква команда ще използвате, за да покажете историята на използваните команди в текущата сесия?
history
[root@ localhost ~ ]# history
  1 history
  2 clear
  3 history
  4 clear
  5 history

2. Каква е функцията на променливата PATH в операционната система?

PATH: Списък с директории, в които операционната система търси изпълнимите файлове.
HOME: Домашната директория на текущия потребител.
USER: Името на текущия потребител.
SHELL: Пътят до обвивката (shell), използвана в текущата сесия.
PWD: Текущата работна директория.
LANG: Задава езика, използван за извеждане на грешки и друга локализирана информация.
TERM: Типът на терминала.
DISPLAY: Дисплеят на X-сървъра, на който ще се показват графичните приложения.
EDITOR: Текстовият редактор, използван по подразбиране.
TZ: Часовата зона на системата.

3. Как ще добавите нова директория към променливата PATH?

export PATH="/нова/директория:$PATH"
export LANG="bg_BG.UTF-8"
export EDITOR="vim"

4. Как ще зададете нова стойност за променливата HOME?

[root@localhost ~]# export HOME=tmp
[root@localhost ~]# export PWD=tmp
[root@localhost ~]# export OLDPWD=tmp

5. Каква команда ще използвате, за да видите всички променливи на средата и техните стойности?

За да видим стойностите на параметрите на средата, използваме командата env или printenv
Дефинираме свой параметър: export MY_VAR="Hello, World!"

6. Каква команда ще използвате, за да намерите всички файлове в системата, чието име съдържа "hello"?

[root@localhost ~]# find / -type f -name "*hello*"

/usr/lib64/python3.9/__phello__.foo.py
/usr/lib64/python3.9/__pycache__/__phello__.foo.cpython-39.pyc
/usr/lib64/python3.9/__pycache__/__phello__.foo.cpython-39.opt-2.pyc
/usr/lib64/python3.9/__pycache__/__phello__.foo.cpython-39.opt-1.pyc
/usr/lib64/dillo/dpi/hello/hello.filter.dpi
/usr/lib64/python2.7/__phello__.foo.pyo
/usr/lib64/python2.7/__phello__.foo.py
/usr/lib64/python2.7/Demo/tkinter/guido/hello.pyo
/usr/lib64/python2.7/Demo/tkinter/guido/hello.py
/usr/lib64/python2.7/Demo/tkinter/guido/hello.pyc
/usr/lib64/python2.7/__phello__.foo.pyc
/usr/share/systemtap/examples/general/helloworld.meta
/usr/share/systemtap/examples/general/helloworld.stp
/usr/share/systemtap/examples/apps/hello.php

7. Каква команда ще използвате, за да намерите всички файлове в системата, съдържащи текста "hello", и да изведете само имената на файловете?

grep -r -l "hello" /
/root/hello.c
