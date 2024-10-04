```
Connected!
hacker@commands~hidden-files:~$ ls -a
.   .ICEauthority  .bash_logout  .cache   .dbus   .profile  a       me
..  .bash_history  .bashrc       .config  .local  Desktop   delete
hacker@commands~hidden-files:~$ pwd
/home/hacker
hacker@commands~hidden-files:~$ cd ../..
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv           bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-1125795131644  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cd /challenge
hacker@commands~hidden-files:/challenge$ ls -a
.  ..  .init  DESCRIPTION.md  run
hacker@commands~hidden-files:/challenge$ /challenge/run
There's no flag here for you! I made the flag readable but hid it as a .-prepended file in the / directory. Go find it!
hacker@commands~hidden-files:/challenge$ cd ../
hacker@commands~hidden-files:/$ ls -a
.   .dockerenv           bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-1125795131644  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:/$ cat .flag-1125795131644
pwn.college{IG2sqdU_vpPN6z_ZsPH83ejCNEC.dBTN4QDL1EjN0czW}
```

PROCESS: cd ../.. to go to the / directory and then ls -a to find the .flag-1125795131644 file and then cat .flag-1125795131644
