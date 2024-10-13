# Changing permissions

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `ls -l` and then i typed ` chmod ugoa+r /flag` to changepermission of the user and then i used `cat /flag`
then i pasted my flag to the website.

## Bash
`hacker@permissions~changing-permissions:~$ ls -l
total 40
-rw-r--r-- 1 hacker hacker    4 Oct  8 02:57 COLLEGE
-rw-r--r-- 1 hacker hacker    8 Oct  9 09:36 PWN
drwxr-xr-x 2 hacker hacker 4096 Oct  2 04:49 a
-rw-r--r-- 1 root   root     58 Oct  2 05:26 flag
-rw-r--r-- 1 root   hacker   58 Oct  2 04:57 h
-rw-r--r-- 1 hacker hacker  829 Oct  9 09:11 instructions
-rw-r--r-- 1 hacker hacker   93 Oct  9 09:11 myflag
lrwxrwxrwx 1 hacker hacker    5 Oct  2 12:30 not-the-flag -> /flag
-rw-r--r-- 1 hacker hacker   77 Oct  9 13:57 out
-rw-r--r-- 1 root   hacker   77 Oct  9 13:59 temp
-rw-r--r-- 1 hacker hacker  435 Oct  8 03:22 the-flag
hacker@permissions~changing-permissions:~$ chmod ugoa+r /flag
hacker@permissions~changing-permissions:~$ cat /flag
pwn.college{kunDlJ63rfq8-UgUmCTIjh3OwoW.dNzNyUDL3kTN0czW}`

## References
Nothing
