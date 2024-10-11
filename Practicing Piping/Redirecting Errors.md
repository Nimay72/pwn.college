```
Connected!
hacker@piping~redirecting-errors:~$ /challenge/run > myflag 2> instructions
hacker@piping~redirecting-errors:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{EGDMCLTjHUGRR55Fl8CsSFKfVgc.ddjN1QDL1EjN0czW}
```
/challenge/run > myflag 2> instructions is same as

/challenge/run 1> myflag 2> instructions

it redirects the output of /challenge/run to myflag and the "errors" to instructions.
