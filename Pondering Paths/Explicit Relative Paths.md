
# explicit relative paths

## Procedure
I started explicit relative paths.
I went to Ubuntu terminal and typed `ssh -i ./key hacker@dojo.pwn.college`
It connected ubuntu to pwn.college with ssh
Then i typed `/challenge/run`
i got incorrect 
so i use `pwd` to print working directory
and to go back to / directory i used using `cd ..` twice 
and then i  typed `./challenge/run`
and got the flag `pwn.college{kvm5rmHiO6SeEKEEyQGN7rXTKyM.dBTN1QDL3kTN0czW}`

## bash
`Connected!
hacker@paths~explicit-relative-paths-from-:~$ ./challenge/run
ssh-entrypoint: ./challenge/run: No such file or directory
hacker@paths~explicit-relative-paths-from-:~$ pwd
/home/hacker
hacker@paths~explicit-relative-paths-from-:~$ cd ..
hacker@paths~explicit-relative-paths-from-:/home$ cd ..
hacker@paths~explicit-relative-paths-from-:/$ cd ..
hacker@paths~explicit-relative-paths-from-:/$ ./challenges/run
ssh-entrypoint: ./challenges/run: No such file or directory
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{kvm5rmHiO6SeEKEEyQGN7rXTKyM.dBTN1QDL3kTN0czW}`

## Reference
did on my own
