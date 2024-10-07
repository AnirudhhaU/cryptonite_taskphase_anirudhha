# Mixing globs

## Procedure
i started the challenge, and then connected the terminal<br>
and then i used `cd /challenge/files` and then used `/challenge/run [cpe]*`
and then got the flag.

## bash
`hacker@globbing~mixing-globs:~$ cd /chal*
hacker@globbing~mixing-globs:/challenge$ cd /files
ssh-entrypoint: cd: /files: No such file or directory
hacker@globbing~mixing-globs:/challenge$ ls
DESCRIPTION.md  files  run
hacker@globbing~mixing-globs:/challenge$ ls -a
.  ..  .bashrc  DESCRIPTION.md  files  run
hacker@globbing~mixing-globs:/challenge$ cd files
hacker@globbing~mixing-globs:/challenge/files$ ls
amazing      fantastic   kind        pwning     uplifting   zesty
beautiful    great       laughing    queenly    victorious
challenging  happy       magical     radiant    wonderful
delightful   incredible  nice        splendid   xenial
educational  jovial      optimistic  thrilling  youthful
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [c*e*p*]
Error: your argument is too long! It must be 6 characters or less.
hacker@globbing~mixing-globs:/challenge/files$ /challenge/run [cep]*
You got it! Here is your flag!
pwn.college{wpkE0yVRse844r56DyAANEHl8em.dVjM4QDL3kTN0czW}`

## Reference
friends
