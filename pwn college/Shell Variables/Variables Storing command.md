# Variables Storing command

## Procedure
i started the challenge pwn.college
as per the question.
then i typed `PWN=$(env /challenge/run)`
and then used ` echo $PWN`
then i pasted my flag to the website.

## Bash
`Connected!
hacker@variables~storing-command-output:~$ PWN=$(echo /challenge/run)
hacker@variables~storing-command-output:~$ echo $PWN
/challenge/run
hacker@variables~storing-command-output:~$ PWN=$(env /challenge/run)
Congratulations! You have read the flag into the PWN variable. Now print it out
and submit it!
hacker@variables~storing-command-output:~$ echo $PWN
pwn.college{86rCWgZCByAnERmHgcIoASiyruQ.dVzN0UDL3kTN0czW}`

## References
Nothing
