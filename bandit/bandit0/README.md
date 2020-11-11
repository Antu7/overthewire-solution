# Bandit0

link-> https://overthewire.org/wargames/bandit/bandit0.html

## LEVEL GOAL

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

Commands you may need to solve this level
ssh

Helpful Reading Material
Secure Shell (SSH) on Wikipedia
How to use SSH on wikiHow

## SOLUTION

```
antu@root:~/overthewire-bandit/bandit0$ ssh bandit0@bandit.labs.overthewire.org -p 2220
bandit0@bandit.labs.overthewire.org's password: bandit0
bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
boJ9jbbUNNfktd78OOpsqOltutMc3MY1
```  

So `boJ9jbbUNNfktd78OOpsqOltutMc3MY1` is our password to get access into next level

## Note
you also can use those to pass these challenges.

1) more 
2) less 
3) head
4) grep .
5) nano
6) vim