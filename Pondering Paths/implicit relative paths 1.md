```
Connected!
hacker@paths~implicit-relative-paths-from-:~$ challenge/run
ssh-entrypoint: challenge/run: No such file or directory
hacker@paths~implicit-relative-paths-from-:~$ cd ../
hacker@paths~implicit-relative-paths-from-:/home$ challenge/run
ssh-entrypoint: challenge/run: No such file or directory
hacker@paths~implicit-relative-paths-from-:/home$ ../challenge/run
Incorrect...
You are not currently in the / directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~implicit-relative-paths-from-:/home$ ..
ssh-entrypoint: ..: command not found
hacker@paths~implicit-relative-paths-from-:/home$ cd ..
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{A1BxwDO7v_MtMmnrojoqJbkATnB.dlDN1QDL1EjN0czW}
hacker@paths~implicit-relative-paths-from-:/$
```

PROCESS: Invoke challenge/run in a relative manner from / directory instead of absolute manner;
REFERENCE USED: https://linuxhandbook.com/absolute-vs-relative-path/#:~:text=If%20your%20project%20has%20several%20folders%20and%20you%20are%20required
