# implicit relative paths

## Procedure
I started implicit relative paths.
I went to Ubuntu terminal and typed `ssh -i ./key hacker@dojo.pwn.college`
It connected ubuntu to pwn.college with ssh
Then i typed `/challenge/run`
i got incorrect 
so i use `pwd` to print working directory
and to go back to / directory i used using `cd ..` twice 
and then i  typed `challenge/run`
and got the flag `pwn.college{wSuxRSIJBF7Z5NU8MzEkAPdADEW.dlDN1QDL3kTN0czW}`

## bash
`Connected!
hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{wSuxRSIJBF7Z5NU8MzEkAPdADEW.dlDN1QDL3kTN0czW}
hacker@paths~implicit-relative-paths-from-:/$`

## Reference
did on my own
