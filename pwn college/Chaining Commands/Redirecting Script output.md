# Redirecting Script output

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `touch x.sh ` to create a shell script and then i used `echo /challenge/pwn >> x.sh` and `echo /challenge/college >> x.sh`
then i used `bash s.sh | /challenge/solve ` then i pasted my flag to the website.

## Bash
`hacker@chaining~redirecting-script-output:~$ touch s.sh
hacker@chaining~redirecting-script-output:~$ echo /challenge/pwn >> s.sh
hacker@chaining~redirecting-script-output:~$ echo /challenge/college >> s.sh
hacker@chaining~redirecting-script-output:~$ bash s.sh | /challenge/solve
Correct! Here is your flag:
pwn.college{QB2cUlj-0XQsfb5IhX9XnNZ0nXp.dhTM5QDL3kTN0czW}`

## References
nothing
