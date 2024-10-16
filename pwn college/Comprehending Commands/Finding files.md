# Finding files

## Procedure
I started finding files and after connecting to pwn college through ssh
Then i typed `cd /` and went to challenge directory
Then i typed `find -name flag` then i got a list of paths and then use each of the path find the flag by using  `cd ` to go to a directory and then `cat` to 
the flag .After many tries 
then i got flag `pwn.college{srIjN9HQvxm6GSor2PwDBbFqzzt.dJzM4QDL3kTN0czW}`


## bash
`
anirudhha_u@LAPTOP-QOACAGVI:~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
hacker@commands~finding-files:~$ find -name flag
./flag
hacker@commands~finding-files:~$ cat ./flag
pwn.college{k_TcQKdXOlDEI70Sse2sRXALA_m.dFzN1QDL3kTN0czW}
hacker@commands~finding-files:~$ cd /
hacker@commands~finding-files:/$ find -name flag
find: ‘./root’: Permission denied
find: ‘./proc/1/task/1/fd’: Permission denied
find: ‘./proc/1/task/1/fdinfo’: Permission denied
find: ‘./proc/1/task/1/ns’: Permission denied
find: ‘./proc/1/fd’: Permission denied
find: ‘./proc/1/map_files’: Permission denied
find: ‘./proc/1/fdinfo’: Permission denied
find: ‘./proc/1/ns’: Permission denied
find: ‘./proc/7/task/7/fd’: Permission denied
find: ‘./proc/7/task/7/fdinfo’: Permission denied
find: ‘./proc/7/task/7/ns’: Permission denied
find: ‘./proc/7/fd’: Permission denied
find: ‘./proc/7/map_files’: Permission denied
find: ‘./proc/7/fdinfo’: Permission denied
find: ‘./proc/7/ns’: Permission denied
./home/hacker/flag
find: ‘./var/log/private’: Permission denied
find: ‘./var/log/apache2’: Permission denied
find: ‘./var/log/mysql’: Permission denied
find: ‘./var/cache/ldconfig’: Permission denied
find: ‘./var/cache/apt/archives/partial’: Permission denied
find: ‘./var/cache/private’: Permission denied
find: ‘./var/lib/apt/lists/partial’: Permission denied
find: ‘./var/lib/php/sessions’: Permission denied
find: ‘./var/lib/mysql-files’: Permission denied
find: ‘./var/lib/private’: Permission denied
find: ‘./var/lib/mysql-keyring’: Permission denied
find: ‘./var/lib/mysql’: Permission denied
find: ‘./tmp/tmp.XvrUsDZh8M’: Permission denied
find: ‘./run/mysqld’: Permission denied
find: ‘./run/sudo’: Permission denied
find: ‘./etc/ssl/private’: Permission denied
./usr/local/lib/python3.8/dist-packages/pwnlib/flag
./usr/local/share/radare2/5.9.5/flag
./usr/share/doc/clang/flag
./opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
./opt/radare2/libr/flag
./nix/store/pmvk2bk4p550w182rjfm529kfqddnvh3-python3.11-pwntools-4.12.0/lib/python3.11/site-packages/pwnlib/flag
./nix/store/1yagn5s8sf7kcs2hkccgf8d0wxlrv5sz-radare2-5.9.0/share/radare2/5.9.0/flag
hacker@commands~finding-files:/$ cat ./usr/local/lib/python3.8/dist-packages/pwnlib/flag
cat: ./usr/local/lib/python3.8/dist-packages/pwnlib/flag: Is a directory
hacker@commands~finding-files:/$ cd ./usr/local/lib/python3.8/dist-packages/pwnlib/flag
hacker@commands~finding-files:/usr/local/lib/python3.8/dist-packages/pwnlib/flag$ ls
__init__.py  __pycache__  flag.py
hacker@commands~finding-files:/usr/local/lib/python3.8/dist-packages/pwnlib/flag$ cd /
hacker@commands~finding-files:/$ ls ./usr/local/share/radare2/5.9.5/flag
tags.r2
hacker@commands~finding-files:/$ cat ./usr/local/share/radare2/5.9.5/flag
cat: ./usr/local/share/radare2/5.9.5/flag: Is a directory
hacker@commands~finding-files:/$ ls ./usr/share/doc/clang/flag
./usr/share/doc/clang/flag
hacker@commands~finding-files:/$ cat ./usr/share/doc/clang/flag
pwn.college{srIjN9HQvxm6GSor2PwDBbFqzzt.dJzM4QDL3kTN0czW}`

## Reference
did on my own
