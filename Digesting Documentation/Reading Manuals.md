```
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                                      Challenge Commands                                     CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --ldvgqd NUM
              print the flag if NUM is 764

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-luminarium/>

SEE ALSO
       man(1) bash-builtins(7)
hacker@man~reading-manuals:~$
hacker@man~reading-manuals:~$ challenge/challenge ---ldvgqd 764
ssh-entrypoint: challenge/challenge: No such file or directory
hacker@man~reading-manuals:~$ cd ../
hacker@man~reading-manuals:/home$ cd ../
hacker@man~reading-manuals:/$ ls
bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@man~reading-manuals:/$ challenge/challenge ---ldvgqd 764
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:/$ challenge/challenge --ldvgqd 764
Correct usage! Your flag: pwn.college{Ql7d6v481g_7_ZBqdlCmXN7CM4I.dRTM4QDL1EjN0czW}
```

PROCESS: man challenge to open challenge manual, quit the manual and cd to the / directory and then challenge/challenge --ldvgqd 764 as the manual says.
