# Fun with groups

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `id` and then i typed ` chgrp grp15696 /flag` and went through the user and then i used `cat /flag`
then i pasted my flag to the website.

## Bash
`hacker@permissions~fun-with-groups-names:~$
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp15696) groups=1000(grp15696)
hacker@permissions~fun-with-groups-names:~$ chgrp grp15696 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{Ylu7Lbn1OhpSxtNSroEDcbdp8Hz.dJzNyUDL3kTN0czW}`

## References
Nothing
