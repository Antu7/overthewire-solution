# bandit8

link-> https://overthewire.org/wargames/bandit/bandit8.html

## LEVEL GOAL

The password for the next level is stored in the file data.txt next to the word millionth

Commands you may need to solve this level
grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xx7

## SOLUTION

```
antu@root:~/overthewire-bandit/bandit8$ ssh bandit8@bandit.labs.overthewire.org -p 2220
bandit8@bandit.labs.overthewire.org's password: cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit8@bandit:~$ ls
bandit8@bandit:~$ 
data.txt
bandit8@bandit:/home$ cat data.txt
```
The file called data.txt contained to much data and it's hard too find our flag which is next to our word millionth
```
bandit8@bandit:~$ cat data.txt | grep millionth
millionth	cvX2JJa4CFALtqS87jk27qwqGhBM9plV
````

So `cvX2JJa4CFALtqS87jk27qwqGhBM9plV` is our password to get access into next level
