
# Reading manuals

## Procedure
I started Reading manuals and after connecting to pwn college through ssh
Then i typed `man challenge`and got  list of commands 
and i use `/challenge/challenge --cifhob 228`
got the flag `pwn.college{MHI-KlI-NKDgWfjrZPrNhefisNP.dVjM5QDL3kTN0czW}`

## bash
`                                                                          Connected!
hacker@man~reading-manuals:~$ man challenge
CHALLENGE(1)                Challenge Commands                CHALLENGE(1)
NAME
       /challenge/challenge - print the flag!
SYNOPSIS
       challenge OPTION
DESCRIPTION
       Output the flag when called with the right arguments.
       --fortune
              read a fortune
       --version
              output version information and exit
       --cifhob NUM
              print the flag if NUM is 228
AUTHOR
       Written by Zardus.
REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-
       luminarium/>
SEE ALSO
       man(1) bash-builtins(7)
pwn.college                      May 2024                     CHALLENGE(1)
hacker@man~reading-manuals:~$ ^C
hacker@man~reading-manuals:~$ /challenge/challenge
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$ /challenge/challenge --cifhob 228
Correct usage! Your flag: pwn.college{M2c2ZCG-G-iOfhobXayK8J4oEVb.dRTM4QDL3kTN0czW}`

## Reference
did on my own
