# Backgrounded processes

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `/challenge/run &` and
then i pasted my flag to the website.

## Bash
`Connected!
hacker@processes~starting-backgrounded-processes:~$ /challenge/run
You've started me in the foreground! You must start me in the background (by
appending '&' to the command) to get the flag!
hacker@processes~starting-backgrounded-processes:~$ bg
ssh-entrypoint: bg: current: no such job
hacker@processes~starting-backgrounded-processes:~$ /challenge/run &
[1] 85
Yay, you started me in the background! Because of that, this text will probably
overlap weirdly with the shell prompt, but you're used to that by now...
Anyways! Here is your flag!
pwn.college{QHWVFYQFyKyV_NPSXJXA4MOwYFH.dlDN4QDL3kTN0czW}
[1]+  Done                    /challenge/run`

## References
Nothing
