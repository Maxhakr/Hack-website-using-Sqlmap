# Hack-website-using-Sqlmap
Requirements :
Termux App
SQL-Map (Its Important for hack website)
Hacker’s Keybord
FileManager
Patience & Brain
SQLMap Installation Method :
SQLmap is the one of the most Popular and powerful SQL injection tool out there. Given a vulnerable http request URL, sqlmap can exploit database and tables.

Its Return on Python so need to install python on your termux

For the list of options and parameters that can be used with the sqlmap command, check the sqlmap documentation at here.

Steps to Install SQLMAP:
First download the all app above Mentions.
Now Open termux and Follow my commands.
First Give command $ apt update & apt upgrade
$ pkg install python
$ pkg install python2
$ git clone https://github.com/sqlmapproject/sqlmap
$ ls
$ cd sqlmap-master
$ ls
Now you run the sqlmap
$ python2 sqlmap.py (If you see this red color sqlmap then relax yourself! You are done with the installation of sqlmap. Now next step is hacking the website using sqlmap. You need to find a website with SQL vulnerability. For this, use sqlmap google dork to find websites.)
If you using the dork the do command. $ python2 sqlmap.py -g Your_dork
If you want using direct URL then do command, $ python2 sqlmap.py -u Your_URL
If you want help then you simply type $ python2 sqlmap.py -h (itmis for basic help)
For advance help type $ python2 sqlmap.py -hh
If you want to hack website database and tables then type the command $python2 sqlmap.py -g your_dork or $ python2 sqlmap.py -u your_URL
In google dork method, it will give you three option :
Yes for attacking first site, which comes in result. For proceeding further, you need to type “y”.
For skipping to the next target you can use “n”
For quitting, use “q”.
Attacking Start
