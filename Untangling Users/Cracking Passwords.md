# Cracking passwords

## Procedure
i started the challenge pwn.college
as per the question.  
then i typed `john ./shadow-leak` and then i got the password `dont-hack-me` to get access of zardus user and then i typed  `su zardus`and typed the password and then i ran`/challenge/run`
then i pasted my flag to the website.

## Bash
`hacker@users~cracking-passwords:/challenge$ john ./shadow-leak
Loaded 1 password hash (crypt, generic crypt(3) [?/64])
Press 'q' or Ctrl-C to abort, almost any other key for status
aardvark         (zardus)
1g 0:00:00:20 100% 2/3 0.04965g/s 289.1p/s 289.1c/s 289.1C/s Johnson..buzz
Use the "--show" option to display all of the cracked passwords reliably
Session completed
hacker@users~cracking-passwords:/challenge$ su zardus
Password:
zardus@users~cracking-passwords:/challenge$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{g1ISkORWXZWYVBe3sD8xchs3s5g.ddTN0UDL3kTN0czW}`

## References
Nothing , i actually felt like a hacker 
