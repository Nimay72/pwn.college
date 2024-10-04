**Position elsewhere**

```
Connected!
hacker@paths~position-elsewhere:~$ /challenge/run
Incorrect...
You are not currently in the /var/lib/apt/lists directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-elsewhere:~$ cd /var/lib/apt/lists
hacker@paths~position-elsewhere:/var/lib/apt/lists$ challenge/run
ssh-entrypoint: challenge/run: No such file or directory
hacker@paths~position-elsewhere:/var/lib/apt/lists$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{oVJXhQDj1aAR3VNdfl0fw1eDRHf.ddDN1QDL1EjN0czW}
hacker@paths~position-elsewhere:/var/lib/apt/lists$
```

PROCESS:
invoked /challenge/run initially 
got an error saying cd into /var/lib/apt/lists
did that then invoked /challenge/run 
