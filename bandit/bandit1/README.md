# Bandit0

link-> https://overthewire.org/wargames/bandit/bandit1.html

## LEVEL GOAL

The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Commands you may need to solve this level
ls, cd, cat, file, du, find

## SOLUTION

```
antu@root:~/overthewire-bandit/bandit1$ ssh bandit1@bandit.labs.overthewire.org -p 2220
bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
```  

So `CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9` is our password to get access into next level

## Note
you also can use those to pass these challenges.

1) more 
2) less 
3) head
4) grep .
5) nano
6) vim