
# An Epic Filesystem Quest

## Procedure
I started An Epic Filesystem Quest and after connecting to pwn college through ssh
Then i typed `cd /` to go to / directory
Then i typed `ls -a` and
then to find flag in file i typed `grep pwn.college .flag-253112264625024`
and got the flag `wn.college{YfiqGxr_2ZHK29zHFWNDhf3RfQl.dBTN4QDL3kTN0czW}`

## bash
`Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
MEMO  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin   challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat MEMO
Congratulations, you found the clue!
The next clue is in: /usr/share/javascript/mathjax/unpacked/localization/en
The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/javascript/mathjax/unpacked/localization/en
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/localization/en$ ls
BRIEF  FontWarnings.js  HTML-CSS.js  HelpDialog.js  MathML.js  MathMenu.js  TeX.js  en.js
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/localization/en$ cat BRIEF
Tubular find!
The next clue is in: /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Neo-Euler/Size4/Regular
Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/localization/en$ ls /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Neo-Euler/Size4/Regular
DOSSIER-TRAPPED  Main.js
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/localization/en$ cat /usr/share/javascript/mathjax/unpacked/jax/output/SVG/fonts/Neo-Euler/Size4/Regular/DOSSIER-TRAPPED
Great sleuthing!
The next clue is in: /usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular
The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/unpacked/localization/en$ cd /usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular$ ls
CUE  Main.js
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular$ cat /usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular/CUE
Tubular find!
The next clue is in: /usr/share/dwarves/runtime
Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular$ ls /usr/share/dwarves/runtime
Makefile  README-TRAPPED  ctracer_relay.c  ctracer_relay.h  linux.blacklist.cu
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular$ cat /usr/share/dwarves/runtime/README-TRAPPED
Lucky listing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/json5/__pycache__
The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/share/javascript/mathjax/jax/output/SVG/fonts/Latin-Modern/Fraktur/Regular$ cd /usr/local/lib/python3.8/dist-packages/json5/__pycache__
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/json5/__pycache__$ ls -a
.            __init__.cpython-38.pyc    host.cpython-38.pyc    tool.cpython-38.pyc
..           __main__.cpython-38.pyc    lib.cpython-38.pyc     version.cpython-38.pyc
.REVELATION  arg_parser.cpython-38.pyc  parser.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/json5/__pycache__$ cat /usr/local/lib/python3.8/dist-packages/json5/__pycache__/.REVELATION
Yahaha, you found me!
The next clue is in: /usr/share/racket/collects/ffi
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/json5/__pycache__$ cd /usr/share/racket/collects/ffi
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ ls
MESSAGE           com.rkt   cvector.rkt  objc.rkt  unsafe.rkt  winapi.rkt
com-registry.rkt  compiled  file.rkt     unsafe    vector.rkt
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ cat /usr/share/racket/collects/ffi/MESSAGE
Tubular find!
The next clue is in: /usr/share/X11/xkb/symbols/digital_vndr
Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ ls /usr/share/X11/xkb/symbols/digital_vndr
BLUEPRINT-TRAPPED  lk  pc  us  vt
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ cat /usr/share/X11/xkb/symbols/digital_vndr/BLU
EPRINT-TRAPPED
Lucky listing!
The next clue is in: /usr/local/lib/python3.8/dist-packages/pysmt/solvers/__pycache__
Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ ls /usr/local/lib/python3.8/dist-packages/pysmt/solvers/__pycache__
DISPATCH-TRAPPED         cvcfour.cpython-38.pyc        pico.cpython-38.pyc       yices.cpython-38.pyc
__init__.cpython-38.pyc  eager.cpython-38.pyc          portfolio.cpython-38.pyc  z3.cpython-38.pyc
bdd.cpython-38.pyc       interpolation.cpython-38.pyc  qelim.cpython-38.pyc
btor.cpython-38.pyc      msat.cpython-38.pyc           smtlib.cpython-38.pyc
cvcfive.cpython-38.pyc   options.cpython-38.pyc        solver.cpython-38.pyc
hacker@commands~an-epic-filesystem-quest:/usr/share/racket/collects/ffi$ cat /usr/local/lib/python3.8/dist-packages/pysmt/solvers/__pycache__/DISPATCH-TRAPPED
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!`

## Reference
did on my own
