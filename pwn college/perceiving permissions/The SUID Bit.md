# The SUID Bit

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `/challenge/getroot` and then i typed `ls -l /challenge/getroot` to list the user and then i used `/challenge/getroot ` to run the program and then i used `cat /flag`
then i pasted my flag to the website.

## Bash
`hacker@permissions~the-suid-bit:~$ chmod u+r /challenge/getroot
hacker@permissions~the-suid-bit:~$ ls -l /challenge/getroot
-rwsr-xr-x 1 root root 155 Jul 12 10:30 /challenge/getroot
hacker@permissions~the-suid-bit:~$ /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root!
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{IdXGXZEtjuituUPt5Uviucbc0Y3.dNTM2QDL3kTN0czW}`

## References
Nothing
