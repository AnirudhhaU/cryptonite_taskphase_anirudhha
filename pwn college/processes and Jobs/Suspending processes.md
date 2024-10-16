# 

## Procedure
i started the challenge pwn.college
as per the question.
then i typed `/challenge/run` i used `ctrl z` to stop the process and then again ran ` /challenge/run`
then i pasted my flag to the website.

## Bash
`Connected!
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!
UID          PID    PPID  C STIME TTY          TIME CMD
root          83      65  0 07:58 pts/0    00:00:00 bash /challenge/run
root          85      83  0 07:58 pts/0    00:00:00 ps -f
I don't see a second me!
To pass this level, you need to suspend me and launch me again! You can
background me with Ctrl-Z or, if you're not ready to do that for whatever
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ ^C
hacker@processes~suspending-processes:~$ ^C
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!
UID          PID    PPID  C STIME TTY          TIME CMD
root          83      65  0 07:58 pts/0    00:00:00 bash /challenge/run
root          90      65  0 07:59 pts/0    00:00:00 bash /challenge/run
root          92      90  0 07:59 pts/0    00:00:00 ps -f
Yay, I found another version of me! Here is the flag:
pwn.college{sx3yFQOiAG67POedv30w9b0Ekkk.dVDN4QDL3kTN0czW}`

## References
Nothing
