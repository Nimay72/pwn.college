```
Connected!
hacker@man~learning-complex-usage:~$ pwd
/home/hacker
hacker@man~learning-complex-usage:~$ cd ../..
hacker@man~learning-complex-usage:/$ ls -a
.   .dockerenv  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
..  bin         challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@man~learning-complex-usage:/$ /challenge/challenge --printfile /flag
Correct argument! Here is the /flag file:
pwn.college{I9K5LNviFJcqkpnuWOWPW7BC2BJ.dVjM5QDL1EjN0czW}
```

PROCESS:
Find flag file which was there in / directory and then use the command /challenge/challenge --printfile /flag to print the contents of thr file.
