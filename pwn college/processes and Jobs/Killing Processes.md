# Killing Processes

## Procedure
i started the challenge pwn.college
as per the question.
then i typed `ps -e` and then i used `/challenge/run`
then i pasted my flag to the website.

## Bash
`Connected!
hacker@processes~killing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 07:46 ?        00:00:00 /sbin/docker-init -- /ni
root           7       1  0 07:46 ?        00:00:00 /run/dojo/bin/sleep 6h
root          71       1  0 07:46 ?        00:00:00 su -c /challenge/.launch
hacker        73      71  0 07:46 ?        00:00:00 /challenge/dont_run
hacker        74      73  0 07:46 ?        00:00:00 sleep 6h
hacker        75       0  0 07:46 pts/0    00:00:00 /run/dojo/bin/ssh-entryp
hacker        92      75  0 07:48 pts/0    00:00:00 ps -ef
hacker@processes~killing-processes:~$ ps -e
    PID TTY          TIME CMD
      1 ?        00:00:00 docker-init
      7 ?        00:00:00 /run/dojo/bin/s
     71 ?        00:00:00 su
     73 ?        00:00:00 bash
     74 ?        00:00:00 sleep
     75 pts/0    00:00:00 ssh-entrypoint
     93 pts/0    00:00:00 ps
hacker@processes~killing-processes:~$ kill 73
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{UAhU7Pf9_jiR0OSdMCZETwfnbCl.dJDN4QDL3kTN0czW}`

## References
Nothing
