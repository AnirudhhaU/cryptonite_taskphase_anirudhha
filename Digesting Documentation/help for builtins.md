
# Searching manuals

## Procedure
I started Searching manuals and after connecting to pwn college through ssh
Then i typed `help`and got  list of commands 
and i use `help challenge`to find flag command
and used `challenge --secret kHWzBHSn`
got the flag ` pwn.college{kHWzBHSn1XLuSHXMxoFSFXnTG6v.dRTM5QDL3kTN0czW}`

## bash
`hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!
    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct
    You must be sure to provide the right value to --secret. That value
    is "kHWzBHSn".
hacker@man~help-for-builtins:~$ challenge --secret kHWzBHSn
Correct! Here is your flag!
pwn.college{kHWzBHSn1XLuSHXMxoFSFXnTG6v.dRTM5QDL3kTN0czW}                                                                    `

## Reference
took help from friend
