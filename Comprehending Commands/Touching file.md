
# Listing Files

## Procedure
I started Listing Files and after connecting to pwn college through ssh
Then i typed `cd /tmp` and went to challenge directory
Then i typed `ls`
then to create new file i typed `touch pwn`
then similarly i created another file by using `touch college`
and the i typed `/challenge/run`
and got the flag `pwn.college{4wXxE-pv0kRcl_tu-Io8kDFZEmm.dBzM4QDL3kTN0czW}`

## bash
`Connected!
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.XvrUsDZh8M
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.XvrUsDZh8M
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{4wXxE-pv0kRcl_tu-Io8kDFZEmm.dBzM4QDL3kTN0czW}`

## Reference
did on my own
