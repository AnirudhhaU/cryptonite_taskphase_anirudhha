# Exclusionary globbing

## Procedure
i started the challenges and then connected my terminal.<br>
and then i went into `cd/challenge/files` and then used `/challenge/run [!pwn]*` to 
remove all of those paths from files. i got the flag and pasted it into the flag box.

## bash
`Connected!
hacker@globbing~exclusionary-globbing:~$ cd /challenge
hacker@globbing~exclusionary-globbing:/challenge$ cd files
hacker@globbing~exclusionary-globbing:/challenge/files$ cd ../
hacker@globbing~exclusionary-globbing:/challenge$ cd ../
hacker@globbing~exclusionary-globbing:/$ cd ../
hacker@globbing~exclusionary-globbing:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@globbing~exclusionary-globbing:/$ pwd
/
hacker@globbing~exclusionary-globbing:/$ cd /files
ssh-entrypoint: cd: /files: No such file or directory
hacker@globbing~exclusionary-globbing:/$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ ls
amazing      fantastic   kind        pwning     uplifting   zesty
beautiful    great       laughing    queenly    victorious
challenging  happy       magical     radiant    wonderful
delightful   incredible  nice        splendid   xenial
educational  jovial      optimistic  thrilling  youthful
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[!pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[^pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [^pwn]*
You got it! Here is your flag!
pwn.college{A70btv91R3t6R7ffyNkLiyPVi1x.dZjM4QDL3kTN0czW}`

## Reference
Real friend
