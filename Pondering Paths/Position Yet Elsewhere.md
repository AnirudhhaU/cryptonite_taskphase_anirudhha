# Position yet elsewhere

## Procedure
I started position yet elsewhere.
I went to Ubuntu terminal and typed `ssh -i ./key hacker@dojo.pwn.college`
It connected ubuntu to pwn.college with ssh
Then i typed `/challenge/run`
i got incorrect 
and it was in a differnet directory
so to change directory i typed `cd /proc/85`
and then i  typed `/challenge/run`
and got the flag `pwn.college{YZMatHpCGKepRjWcF8SGWtse5Y3.dhDN1QDL3kTN0czW}`

## bash
`Connected!
hacker@paths~position-yet-elsewhere:~$  /challenge/run
Incorrect...
You are not currently in the /proc/85 directory.
Please use the cd utility to change directory appropriately.
hacker@paths~position-yet-elsewhere:~$ cd /proc/85
hacker@paths~position-yet-elsewhere:/proc/85$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{YZMatHpCGKepRjWcF8SGWtse5Y3.dhDN1QDL3kTN0czW}`
