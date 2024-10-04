```
Connected!
hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
pwn.college{Q8QDDT-5zHxwLIK30i3CLqOGyv9.dNzM4QDL1EjN0czW}
```

PROCESS:  /challenge/run ~/a
This command would write the file contents to a which is the argument to the file and this satisfies all the 3 conditions:
```
1) Your argument must be an absolute path.
2) The path must be inside your home directory.
3) Before expansion, your argument must be three characters or less.
```
