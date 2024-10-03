**Position thy self**

```
Connected!
hacker@paths~position-thy-self:~$ cd /usr/bin
hacker@paths~position-thy-self:/usr/bin$ cd /challenge/run
ssh-entrypoint: cd: /challenge/run: Not a directory
hacker@paths~position-thy-self:/usr/bin$ /challenge
ssh-entrypoint: /challenge: Is a directory
hacker@paths~position-thy-self:/usr/bin$ /run
ssh-entrypoint: /run: Is a directory
hacker@paths~position-thy-self:/usr/bin$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{0sdlEcaUBmhJiiDrQ0_YMq7gKWn.dZDN1QDL1EjN0czW}
hacker@paths~position-thy-self:/usr/bin$
```

PROCESS:
cd into usr/bin
invoke /challenge/run
reference used: https://linuxize.com/post/linux-cd-command/
