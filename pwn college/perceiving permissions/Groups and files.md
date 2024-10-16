# Groups and files

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `chgrp hacker /flag` and then i typed `ls -l` and went through the user and then i used `cat not-the-flag`
then i pasted my flag to the website.

## Bash
`hacker@permissions~groups-and-files:~$ chgrp hacker /flag
hacker@permissions~groups-and-files:~$ ls -l
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
hacker@permissions~groups-and-files:~$ cat not-the-flag
pwn.college{UhTa_oGsSNhU_-ws096E4uJG8Nu.dFzNyUDL3kTN0czW}`

## References
Nothing
