```
Connected!
This challenge resets your working directory to /home/hacker unless you change
directory properly...
hacker@globbing~matching-with-:~$ cd /?ha??enge
hacker@globbing~matching-with-:/challenge$ ./run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{EtDFH_1Z_yzKQ9KFYGFHMBR6wMZ.dJjM4QDL1EjN0czW}
```

PROCESS:
Now the challenge asks us to use ? everywhere in the word challenge wherever we see the letters c and l.
? only works for one character unlike * so we use it for different characters. 
challenge directory now becomes ?ha??enge in the command.
