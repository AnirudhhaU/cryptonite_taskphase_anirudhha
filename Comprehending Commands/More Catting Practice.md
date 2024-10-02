
# More Catting Practice

## Procedure
I started catting absolute paths and after connecting to pwn college through ssh
got the absolute directory in the terminal
and then i typed `cat /lib/x86_64-linux-gnu/gstreamer1.0/flag`
and got the flag `pwn.college{sQv-stbsSGc_mx_fxRmXROD5556.dBjM5QDL3kTN0czW}`

## bash
`Connected!
You cannot use the 'cd' command in this level, and must retrieve the flag by
absolute path. Plus, I hid the flag in a different directory! You can find it
in the file /lib/x86_64-linux-gnu/gstreamer1.0/flag. Go cat it out **without**
cding into that directory!
hacker@commands~more-catting-practice:~$ cat /lib/x86_64-linux-gnu/gstreamer1.0/flag
pwn.college{sQv-stbsSGc_mx_fxRmXROD5556.dBjM5QDL3kTN0czW}`

## Reference
did on my own
