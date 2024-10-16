# Excutable shell scripts

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `touch script.sh ` to create a shell script and then i used `echo /challenge/solve >> script.sh`
then i used `chmod ugoa+x script.sh ` to give permission to user to execute and then i used `/home/hacker/script.sh` 
then i pasted my flag to the website.

## Bash
`Connected!
hacker@chaining~executable-shell-scripts:~$ touch script.sh
hacker@chaining~executable-shell-scripts:~$ echo /challenge/solve >> script.sh
hacker@chaining~executable-shell-scripts:~$ chmod ugoa+x script.sh
hacker@chaining~executable-shell-scripts:~$ ./home/hacker/script.sh
ssh-entrypoint: ./home/hacker/script.sh: No such file or directory
hacker@chaining~executable-shell-scripts:~$ /home/hacker/script.sh
Congratulations on your shell script execution! Your flag:
pwn.college{ULhAFUgHh1v48CVa8o-KlTI540b.dRzNyUDL3kTN0czW}`

## References
did not use
