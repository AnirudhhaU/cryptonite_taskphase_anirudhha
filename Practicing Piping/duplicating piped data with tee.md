# duplicating piped data with tee

## Procedure
I started the challenge, and connected the terminal<br>
and then i used `/challenge/pwn | tee temp |
/challenge/college`  and then used `cat temp` got the the secrete code and then used ` /challenge/pwn --secret gNx
ahAaJ | /challenge/college` and got
the flag, i pasted that into the flag box.

## bash
`Connected!
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee temp |
/challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$ cat temp
Usage: /challenge/pwn --secret [SECRET_ARG]
SECRET_ARG should be "gNxahAaJ"
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn --secret gNx
ahAaJ | /challenge/college
Processing...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{gNxahAaJ13ByOz8vV8eQGYliXjI.dFjM5QDL3kTN0czW}`

## Reference
Didnt use
