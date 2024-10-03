
# Searching manuals

## Procedure
I started Searching manuals and after connecting to pwn college through ssh
Then i typed `man challenge`and got  list of commands 
and i use `/ flag `to find flag command
and used `/challenge/challenge --abaib`
got the flag ` pwn.college{Ij1xZSOY3z1V0K5MSuVTvq5nLgD.dVTM4QDL3kTN0czW}`

## bash
`                                                                             Connected!
hacker@man~searching-manuals:~$ man challenge
hacker@man~searching-manuals:~$ --abaib
ssh-entrypoint: --abaib: command not found
hacker@man~searching-manuals:~$ /challenge --abaib
ssh-entrypoint: /challenge: Is a directory
hacker@man~searching-manuals:~$ --abaib flag
ssh-entrypoint: --abaib: command not found
hacker@man~searching-manuals:~$ /challenge/challenge --abaib
Initializing...
Correct usage! Your flag: pwn.college{Ij1xZSOY3z1V0K5MSuVTvq5nLgD.dVTM4QDL3kTN0czW}`

## Reference
did on my own
