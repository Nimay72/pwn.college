```
Connected!
hacker@piping~redirecting-more-output:~$ /challenge/run > myflag
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge will check that output is redirected to a specific file path : myflag
[INFO] - the challenge will output a reward file if all the tests pass : /flag

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /flag file.

[TEST] You should have redirected my stdout to a file called myflag. Checking...

[PASS] The file at the other end of my stdout looks okay!
[PASS] Success! You have satisfied all execution requirements.
hacker@piping~redirecting-more-output:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{ETubM9KH_E0UDI1CS7ePzBZWvbP.dVjN1QDL1EjN0czW}
```

PROCESS:
/challenge/run > myflag
this writes the content of the file /challenge/run to the file myflag.
This is what the challenge asks for.
After redirecting its content to myflag, we are supposed to read the file or catch its content by using cat command and then we get the flag.
