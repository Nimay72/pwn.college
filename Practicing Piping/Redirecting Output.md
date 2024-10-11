```
Connected!
You have created the COLLEGE file and wrote the right value to it, but it
doesn't look like you did it via input redirection.
hacker@piping~redirecting-output:~$ echo PWN > COLLEGE
Correct! You successfully redirected 'PWN' to the file 'COLLEGE'! Here is your
flag:
pwn.college{4of8cVv4it3dSQu_B-XCPBL-lC1.dRjN1QDL1EjN0czW}
```

PROCESS:
echo hi > asdf writes hi to file asdf
so echo PWN > COLLEGE writes PWN to file COLLEGE
the challenge required us to do that.
use the command and get the flag.
