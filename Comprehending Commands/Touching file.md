Connected!
hacker@commands~touching-files:~$ cd /twp
ssh-entrypoint: cd: /twp: No such file or directory
hacker@commands~touching-files:~$ cd /tmp
hacker@commands~touching-files:/tmp$ touch pwn
hacker@commands~touching-files:/tmp$ ls
bin  hsperfdata_root  pwn  tmp.XvrUsDZh8M
hacker@commands~touching-files:/tmp$ touch college
hacker@commands~touching-files:/tmp$ ls
bin  college  hsperfdata_root  pwn  tmp.XvrUsDZh8M
hacker@commands~touching-files:/tmp$ /challenge/run
Success! Here is your flag:
pwn.college{4wXxE-pv0kRcl_tu-Io8kDFZEmm.dBzM4QDL3kTN0czW}
