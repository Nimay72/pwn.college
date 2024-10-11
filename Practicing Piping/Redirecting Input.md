```
Connected!
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{YiKzQfwbRtba2EhjZJ12N-LCpYl.dBzN1QDL1EjN0czW}
```

write the word college in pwn.
then redirect the PWN file to /challenge/run using <.
