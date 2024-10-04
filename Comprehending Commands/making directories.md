```
hacker@commands~making-directories:~$ pwd
/home/hacker
hacker@commands~making-directories:~$ cd ../..
hacker@commands~making-directories:/$ mkdir tmp
mkdir: cannot create directory ‘tmp’: File exists
hacker@commands~making-directories:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~making-directories:/$ cd home
hacker@commands~making-directories:/home$ cd hacker
hacker@commands~making-directories:~$ ls
Desktop  a  delete  me
hacker@commands~making-directories:~$ cd ../..
hacker@commands~making-directories:/$ cd tmp
hacker@commands~making-directories:/tmp$ ls
bin  hsperfdata_root  tmp.XvrUsDZh8M
hacker@commands~making-directories:/tmp$ mkdir pwn
hacker@commands~making-directories:/tmp$ cd pwn
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Uh oh! /tmp/pwn/college does not exist. Please use the 'touch' command to
create it!
hacker@commands~making-directories:/tmp/pwn$ touch college
hacker@commands~making-directories:/tmp/pwn$ /challenge/run
Success! Here is your flag:
pwn.college{cPZUQmWoAW55H-AGE_jcdw0qQpn.dFzM4QDL1EjN0czW}
```
PROCESS: Go to / directory and find the tmp directory and then make a new directory called pwd using mkdir command and then use touch command to create a file named college and then /challenge/run to get the flag.
