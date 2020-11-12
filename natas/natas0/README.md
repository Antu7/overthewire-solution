# natas0

link-> https://overthewire.org/wargames/natas/natas0.html

## LEVEL GOAL

Natas teaches the basics of serverside web-security.

Each level of natas consists of its own website located at http://natasX.natas.labs.overthewire.org, where X is the level number. There is no SSH login. To access a level, enter the username for that level (e.g. natas0 for level 0) and its password.

Each level has access to the password of the next level. Your job is to somehow obtain that next password and level up. All passwords are also stored in /etc/natas_webpass/. E.g. the password for natas5 is stored in the file /etc/natas_webpass/natas5 and only readable by natas4 and natas5.

Start here:

Username: natas0 <br>
Password: natas0 <br>
URL:      http://natas0.natas.labs.overthewire.org <br>

## SOLUTION

The level is simple to go to http://natas0.natas.labs.overthewire.org/ url and use natas0 & natas0 as username password
and we are login so its show a message that `You can find the password for the next level on this page.` so `ctrl + u` for 
View the source code and walla The password for natas1 is `gtVrDuiDfck831PqWsLEZy5gyDz1clto`