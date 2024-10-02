
# hidden files

## Procedure
I started Hidden files and after connecting to pwn college through ssh
Then i typed `ls`
then to delete file i typed `rm delete_me`
and the i typed `/challenge/check`
and got the flag `pwn.college{gQWT6aAVhDngLkN39cNhJSmcZdu.dZTOwUDL3kTN0czW}`

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
