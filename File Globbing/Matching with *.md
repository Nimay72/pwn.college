```
Connected!
This challenge resets your working directory to /home/hacker unless you change
directory properly...
hacker@globbing~matching-with-:~$ cd /ch*
hacker@globbing~matching-with-:/challenge$ ./run
You ran me with the working directory of /challenge! Here is your flag:
pwn.college{kaEIkAwgm2OxYa5QSxCOqRLDUoM.dFjM4QDL1EjN0czW}
```

PROCESS:
cd /ch*
the * keyword will make sure all the files with the name ch_____something will be taken into consideration and here we need to go to challenge directory.
After that we simply run it.
