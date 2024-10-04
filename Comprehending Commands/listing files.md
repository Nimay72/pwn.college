```
Connected!
hacker@commands~listing-files:~$ pwd
/home/hacker
hacker@commands~listing-files:~$ cd ../..
hacker@commands~listing-files:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~listing-files:/$ ls /challenge
12991-renamed-run-9677  DESCRIPTION.md
hacker@commands~listing-files:/$ cat /challenge/12991-renamed-run-9677
#!/opt/pwn.college/bash

echo "Yahaha, you found me! Here is your flag:"
cat /flag
hacker@commands~listing-files:/$ /challenge/12991-renamed-run-9677
Yahaha, you found me! Here is your flag:
pwn.college{cpVP3gYn-ZzxzpINjYxoC48dAZP.dhjM4QDL1EjN0czW}
hacker@commands~listing-files:/$
```

PRCOESS: Find the challenge directory by cd ../.. all the way back. Then ls /challenge to find the hidden file. Then run that file by /challenge/12991-renamed-run-9677 command and then you get the flag.
