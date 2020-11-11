# bandit8

link-> https://overthewire.org/wargames/bandit/bandit8.html

## LEVEL GOAL

The password for the next level is stored in the file data.txt and is the only line of text that occurs only once

Commands you may need to solve this level
grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xx7

## SOLUTION

```
antu@root:~/overthewire-bandit/bandit8$ ssh bandit8@bandit.labs.overthewire.org -p 2220
bandit8@bandit.labs.overthewire.org's password: HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit8@bandit:~$ ls
bandit8@bandit:~$ 
data.txt
bandit8@bandit:/home$ sort data.txt | uniq -u
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR
````

So `UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR` is our password to get access into next level
