```
Connected!
hacker@globbing~matching-with-:~$ cd /challenge/files
hacker@globbing~matching-with-:/challenge/files$ /challenge/run/ file_[bash]
ssh-entrypoint: /challenge/run/: Not a directory
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bash]
You got it! Here is your flag!
pwn.college{scnVDRjYimiBI0Yqo1Dre0IF34U.dNjM4QDL1EjN0czW}
```

PROCESS:
change directory to /challenge/files.
now the challenge asks us to run /challenge/run with a single argument that bracket-globs into file_b, file_a, file_s, and file_h, making the command /challenge/run/ file_[bash].
run it and we get the flag.
