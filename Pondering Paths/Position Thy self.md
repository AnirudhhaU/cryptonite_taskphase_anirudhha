# Position Thy Self

## Procedure
I started Position Thy Self.
I went to Ubuntu terminal and typed `ssh -i ./key hacker@dojo.pwn.college`
It connected ubuntu to pwn.college with ssh
Then i typed `/challenge/run`
i got incorrect 
and it was in a differnet directory
so to change directory i typed `cd /usr/include`
and then i  typed `/challenge/run`
and got the flag `pwn.college{YeJFgR0HISYIgwEcucWY8gp4o7K.dZDN1QDL3kTN0czW}`

## bash
`hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /usr/include directory.
Please use the cd utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd
hacker@paths~position-thy-self:~$ cd usr
ssh-entrypoint: cd: usr: No such file or directory
hacker@paths~position-thy-self:~$ cd /usr/include
hacker@paths~position-thy-self:/usr/include$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{YeJFgR0HISYIgwEcucWY8gp4o7K.dZDN1QDL3kTN0czW}`

## Reference
did not use
