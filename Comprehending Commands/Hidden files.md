
# hidden files

## Procedure
I started Hidden files and after connecting to pwn college through ssh
Then i typed `ls` and could not find flag
Then i typed `ls -a` and
then to find flag in file i typed `grep pwn.college .flag-253112264625024`
and got the flag `wn.college{YfiqGxr_2ZHK29zHFWNDhf3RfQl.dBTN4QDL3kTN0czW}`

## bash
`Connected!
hacker@commands~hidden-files:~$ cd /
hacker@commands~hidden-files:/$ ls
bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-253112264625024  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ grep pwn.college .flag-253112264625024
pwn.college{YfiqGxr_2ZHK29zHFWNDhf3RfQl.dBTN4QDL3kTN0czW}`

## Reference
did on my own
