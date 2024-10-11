# Listing Processes

## Procedure
i started the challenge pwn.college
as per the question.
then i typed ` ps -ef` and then typed `/challenge/22818-run-30508`
then i pasted my flag to the website.

## Bash
`hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 07:35 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /run/dojo/bin/sleep 6h
root           7       1  0 07:35 ?        00:00:00 /run/dojo/bin/sleep 6h
root          68       1  0 07:35 ?        00:00:00 /challenge/22818-run-30508
root          72      68  0 07:35 ?        00:00:00 sleep 6h
hacker        73       0  0 07:35 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        94      73  0 07:36 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ /challenge/22818-run-30508
Yahaha, you found me! Here is your flag:
pwn.college{cjZAA_M-7Vi457K8zDeJLHSNC5c.dhzM4QDL3kTN0czW}
Now I will sleep for a while (so that you could find me with 'ps')`

## References
Nothing
