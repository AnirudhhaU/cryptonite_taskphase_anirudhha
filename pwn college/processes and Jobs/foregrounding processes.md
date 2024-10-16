# foregrounding processes

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `/challenge/run` and then i typed `bg` and then used `fg` and then i used `/challenge/run`
then i pasted my flag to the website.

## Bash
`hacker@processes~foregrounding-processes:~$ /challenge/run
To pass this level, you need to suspend me, resume the suspended process in the
background, and *then* foreground it without re-suspending it! You can
background me with Ctrl-Z (and resume me in the background with 'bg') or, if
you're not ready to do that for whatever reason, just hit Enter and I'll exit!
^Z
[3]+  Stopped                 /challenge/run
hacker@processes~foregrounding-processes:~$ bg
[3]+ /challenge/run &
Yay, I'm now running the background! Because of that, this text will probably
overlap weirdly with the shell prompt. Don't panic; just hit Enter a few times
to scroll this text out. After that, resume me into the foreground with 'fg';
I'll wait.
hacker@processes~foregrounding-processes:~$ fg
/challenge/run
YES! Great job! I'm now running in the foreground. Hit Enter for your flag!
pwn.college{0yP762_O3fEc3FDxdQcVCNe4DK3.dhDN4QDL3kTN0czW}`

## References
Nothing
