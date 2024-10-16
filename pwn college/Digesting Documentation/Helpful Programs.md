
# Searching manuals

## Procedure
I started Searching manuals and after connecting to pwn college through ssh
Then i typed `/challenge/challenge --help`and got  list of commands 
and i used ` -p `to print the secret code
and used `/challenge/challenge -g 877`
got the flag `pwn.college{8fihyzyeUGQGjt7EmAz7foiww0m.ddjM4QDL3kTN0czW}`

## bash
`                                                                             
Connected!
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v]
                                            [-g GIVE_THE_FLAG] [-p]
optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to
                        give you the flag
hacker@man~helpful-programs:~$ /challenge/challenge -p
The secret value is: 877
hacker@man~helpful-programs:~$ /challenge/challenge -g 877
Correct usage! Your flag: pwn.college{8fihyzyeUGQGjt7EmAz7foiww0m.ddjM4QDL3kTN0czW}`

## Reference
did on my own
