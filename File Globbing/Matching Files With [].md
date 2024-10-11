```
Connected!
hacker@globbing~matching-paths-with-:~$ /challenge/run file_[/challenge/files bash]
Error: you called this command with more than 1 argument (pre-globbing)! Please
call me with one argument.
hacker@globbing~matching-paths-with-:~$ /challenge/run /challenge/files file_[bash]
Error: you called this command with more than 1 argument (pre-globbing)! Please
call me with one argument.
hacker@globbing~matching-paths-with-:~$ /challenge/run /challenge/files/file_[bash]
You got it! Here is your flag!
pwn.college{4NjB20UOa66beAjP0aSNGgdzaq7.dRjM4QDL1EjN0czW}
```

PROCESS:
run /challenge/run and give the absolute path of the directory and the glob accordingly.
first few attempts were syntax related mistake and the last attempt is the successful attempt to getting the correct command.
