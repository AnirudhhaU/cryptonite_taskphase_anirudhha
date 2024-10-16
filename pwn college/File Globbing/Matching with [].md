# Matching with []

## Procedure
I started the challenge, and connected the terminal<br>
and then i went into `cd /challenge/files` and then used `challenge/run file[bash]` and got 
the flag, i pasted that into the flag box.

## bash
`Connected!
hacker@globbing~matching-with-:~$ cd /
hacker@globbing~matching-with-:/$ cd /challenge
hacker@globbing~matching-with-:/challenge$ ls
DESCRIPTION.md  files  run
hacker@globbing~matching-with-:/challenge$ cd files
hacker@globbing~matching-with-:/challenge/files$
hacker@globbing~matching-with-:/challenge/files$ ls
file_a  file_d  file_g  file_j  file_m  file_p  file_s  file_v  file_y
file_b  file_e  file_h  file_k  file_n  file_q  file_t  file_w  file_z
file_c  file_f  file_i  file_l  file_o  file_r  file_u  file_x
hacker@globbing~matching-with-:/challenge/files$ file_[bash]
ssh-entrypoint: file_a: command not found
hacker@globbing~matching-with-:/challenge/files$ cd file_[bash]
ssh-entrypoint: cd: too many arguments
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{st6sI98QqmeLSm0b4srGxrBW5wp.dNjM4QDL3kTN0czW}`

## Reference
Didnt use
