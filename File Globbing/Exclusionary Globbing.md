```
Connected!
hacker@globbing~exclusionary-globbing:~$ /challenge/files
ssh-entrypoint: /challenge/files: Is a directory
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]*
You got it! Here is your flag!
```

PROCESS:
THE CHALLENGE SAYS the files should not start with p w or n. Using ! at the beginning exactly does so by excluding all files that begin with p,w and n.
Hence, first cd to /challenge/files. Then /challenge/run [!pwn]* to get the flag.
