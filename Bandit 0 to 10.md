# bandid0
##code
'anirudhha_u@LAPTOP-QOACAGVI:~$ ssh bandit0@bandit.labs.overthewire.org -p 2220
kex_exchange_identification: Connection closed by remote host
Connection closed by 16.16.163.126 port 2220
anirudhha_u@LAPTOP-QOACAGVI:~$ ssh bandit0@bandit.labs.overthewire.org -p 2220
                         _                     _ _ _
                        | |__   __ _ _ __   __| (_) |_
                        | '_ \ / _` | '_ \ / _` | | __|
                        | |_) | (_| | | | | (_| | | |_
                        |_.__/ \__,_|_| |_|\__,_|_|\__|


                      This is an OverTheWire game server.
            More information on http://www.overthewire.org/wargames

bandit0@bandit.labs.overthewire.org's password:

      ,----..            ,----,          .---.
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' '
  |   :  | ; | ' ;    |.';  ; ;   \  \;      :
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ;
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"
     \   \ .'        ;   |.'       \   \ ;
  www. `---` ver     '---' he       '---" ire.org


Welcome to OverTheWire!

If you find any problems, please report them to the #wargames channel on
discord or IRC.

--[ Playing the games ]--

  This machine might hold several wargames.
  If you are playing "somegame", then:

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

  Write-access to homedirectories is disabled. It is advised to create a
  working directory with a hard-to-guess name in /tmp/.  You can use the
  command "mktemp -d" in order to generate a random and hard to guess
  directory in /tmp/.  Read-access to both /tmp/ is disabled and to /proc
  restricted so that users cannot snoop on eachother. Files and directories
  with easily guessable or short names will be periodically deleted! The /tmp
  directory is regularly wiped.
  Please play nice:

    * don't leave orphan processes running
    * don't leave exploit-files laying around
    * don't annoy other players
    * don't post passwords or spoilers
    * again, DONT POST SPOILERS!
      This includes writeups of your solution on your blog or website!

--[ Tips ]--

  This machine has a 64bit processor and many security-features enabled
  by default, although ASLR has been switched off.  The following
  compiler flags might be interesting:

    -m32                    compile for 32bit
    -fno-stack-protector    disable ProPolice
    -Wl,-z,norelro          disable relro

  In addition, the execstack tool can be used to flag the stack as
  executable on ELF binaries.

  Finally, network-access is limited for most levls by a local
  firewall.

--[ Tools ]--

 For your convenience we have installed a few useful tools which you can find
 in the following locations:

    * gef (https://github.com/hugsy/gef) in /opt/gef/
    * pwndbg (https://github.com/pwndbg/pwndbg) in /opt/pwndbg/
    * gdbinit (https://github.com/gdbinit/Gdbinit) in /opt/gdbinit/
    * pwntools (https://github.com/Gallopsled/pwntools)
    * radare2 (http://www.radare.org/)

--[ More information ]--

  For more information regarding individual wargames, visit
  http://www.overthewire.org/wargames/

  For support, questions or comments, contact us on discord or IRC.

  Enjoy your stay!'
#bandid1
#code
`
#bandit 0 ->1
## code
`bandit0@bandit:~$ ls
readme
bandit0@bandit:~$ cat readme
Congratulations on your first steps into the bandit game!!
Please make sure you have read the rules at https://overthewire.org/rules/
If you are following a course, workshop, walkthrough or other educational activity,
please inform the instructor about the rules as well and encourage them to
contribute to the OverTheWire community so we can keep these games free!

The password you are looking for is: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
`

#bandit 1-> 2 
##code
`bandit1@bandit:~$ ls
-
bandit1@bandit:~$ cat ./-
263JGJPfgU6LtdEvgfWU1XP5yac29mFx`
# bandit2
## code 
`bandit2@bandit:~$ ls
spaces in this filename
bandit2@bandit:~$ cat "spaces in this filename"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx`

#bandit 2-> 3
## code
`
bandit3@bandit:~/inhere$ ls -a
.  ..  ...Hiding-From-You
bandit3@bandit:~/inhere$ cat ...Hiding-From-You
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
bandit3@bandit:~/inhere$`


#bandit 3-> 4
## code
`bandit4@bandit:~$ ls inhere
-file00  -file02  -file04  -file06  -file08
-file01  -file03  -file05  -file07  -file09
bandit4@bandit:~$ ls -l inhere
total 40
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file00
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file01
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file02
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file03
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file04
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file05
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file06
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file07
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file08
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file09
bandit4@bandit:~$ cat -file09
cat: invalid option -- 'f'
Try 'cat --help' for more information.
bandit4@bandit:~$ cat -- -file09
cat: -file09: No such file or directory
bandit4@bandit:~$ cd inhere
bandit4@bandit:~/inhere$ cat -- -file09
2g��?�����`>5HYA�u���8�g�`0�$`��bandit4@bandit:~/inhere$ cat -- -file08
�nS�
�<��]�
W��e�˥m�����O��D��bandit4@bandit:~/inhere$ cat -- -file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
bandit4@bandit:~/inhere$`

# bandit 4-> 5
## code 
`bandit4@bandit:~$ ls inhere
-file00  -file02  -file04  -file06  -file08
-file01  -file03  -file05  -file07  -file09
bandit4@bandit:~$ ls -l inhere
total 40
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file00
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file01
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file02
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file03
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file04
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file05
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file06
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file07
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file08
-rw-r----- 1 bandit5 bandit4 33 Sep 19 07:08 -file09
bandit4@bandit:~$ cat -file09
cat: invalid option -- 'f'
Try 'cat --help' for more information.
bandit4@bandit:~$ cat -- -file09
cat: -file09: No such file or directory
bandit4@bandit:~$ cd inhere
bandit4@bandit:~/inhere$ cat -- -file09
2g��?�����`>5HYA�u���8�g�`0�$`��bandit4@bandit:~/inhere$ cat -- -file08
�nS�
�<��]�
W��e�˥m�����O��D��bandit4@bandit:~/inhere$ cat -- -file07
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
bandit4@bandit:~/inhere$`

#bandit 5-> 6
## code 
`bandit5@bandit:~$ cd inhere
bandit5@bandit:~/inhere$ find . -type f -size 1033c ! -executable -exec file {} \; | grep 'text'
./maybehere07/.file2: ASCII text, with very long lines (1000)
bandit5@bandit:~/inhere$ cd inhere/maybehere07
-bash: cd: inhere/maybehere07: No such file or directory
bandit5@bandit:~/inhere$ cd inhere/maybehere07
-bash: cd: inhere/maybehere07: No such file or directory
bandit5@bandit:~/inhere$ cat ./maybehere07/.file2
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG`

#bandit 6 -> 7
## code
`bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password
bandit6@bandit:~$ sudo cat /var/lib/dpkg/info/bandit7.password
sudo: /usr/bin/sudo must be owned by uid 0 and have the setuid bit set
bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj`

#bandit 7->8
## code 
`
bandit7@bandit:~$ grep millionth ~/data.txt
millionth       dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
`

# bandit8 -> 9
## code 
`bandit8@bandit:~$ ls
data.txt
bandit8@bandit:~$ sort data.txt | uniq -u
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
`
# bandit 9 ->10
# code 
`bandit9@bandit:~$ strings data.txt | grep '^=*'
h!]v
r>)1
v0i)b
B:PyZ
#0/u
dyaE
F#X[
7$'0'T
^^^K
Y5}|
9g_$
^h#%EG
        Fq/
/OZ[4'
D#?P
POl%
}========== the
db*Nz
cc5M
`oaT
E:zr0
!S:%_
yG@q-
-c5N
xHp\
wS>n
^B~9
Q!vw
'5jl
. \,
66exg
h^Ad
,`Cd80
UB;N
U@j?
p\l=
te24
UNvlE
U%^6
JB]H:|v
|M '
{QMrWv
8:%     XD
H"hU
/uP_
(mhY
+6,hH
4vjm4
q09B
^8NSs
2>X)
Y>v4
lKUO
U>QkM:,V
imZ?L
>^?X
;c<Q=.dEXU!
j!ZL
jX09
5bBK
4Rl_7gH
F 4Cq
#61QW
hqI.X
3JprD========== passwordi
7`4(WG
& `T
_eOdY
G>Wu}
o|)s
z_b^
HCg\@0
z8N_-Z`
v7\y
s>|5
!$L&
Qm1U
JH|)
qi{|p
Yy6]
BWu7
qC(=
"t<2-u
i)W5
Czmnf&v
TO"'
~fDV3========== is
R<+{
)DtZ
)>tgdu
FvkY
Z)w,
|:H5
I;j@
0V[1
d_hnA;
oH`w
7=oc
_N]d
3>\kGG
drfx
}UQB
uP6{
hu%lLj
F>x!&
[^?_
M<ls%
"kz8I
zP=
6o+u
piUv
a*xX$
%!~D
xfvO
Oq.g
(p^A
-45c
^w#K
FP&!
ba+D
n.i3m
GMKB
#s}t
K>]`c
sn)>
v8jB
"x|L
}ZIg
r~rB
+_38
Z@bj:
~de=
.sjd
        qT\
>T`q
Ylyg<
t1QAk
@99F
oxGz$W~"
9+`1
_$>S
J]epm
pfT8
I`8l
fL'~_
a       Z
DT[N
z9wo
5Gfy
"}@>bn
O(k$N
zw[@
!a5^
9Z8]
sqEAj
D)A'r
an      g
'3pp(
s(-Qv
3k=fQ
usTR
Nyz3wI
+)&_i
WDp8
u"o~
p(67
WZ+(
?o&g
k        `
~o=0
6+$N
:'3z
uJw&
&kIIJ
b4glu
]NJR
 %uW
|r_s
zVw-
Q$QBW
Q{h%w
69}=
?uPsH
@WG|
%"=Y
Pew%J
&3[2
*u;(%P
dA`d
|>,p
oY%\
3W`j
D+io?
=tZ~07
^6Og
Tx+X
rs2J
 -M8<
Dq^B
Qv"Y
fk)B
g+;Y
 Uum
D9========== FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
u1Ebi
&x(>G
.`EQ
w>}x
D%(f
1#4!9
:79(
m!}B
| Zd
qQ>Gu
!6D(
J?,2
IEO*
uu>@    ;
KrQ!
$V8a
{vl0pup
AWwyxY
j(ue
X<'j
<HR]/
7!`tcT7
Gp(2
FoOvx
hF|W
3edvE%
_#@k
N=~[!N
-VSe
a0XJ
3;8_
zA=?0j
b}M>s
%Xi-
Qobt
6Cjk
H`U     ^
+v J
4(clh~U
#R^g
Xgz|
)oRj`

# bandit 10 -> 11
# code
`bandit10@bandit:~$ base64 -d data.txt
The password is dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr`


