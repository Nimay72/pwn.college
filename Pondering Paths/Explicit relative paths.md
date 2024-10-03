```
Connected!
hacker@paths~explicit-relative-paths-from-:~$ pwd
/home/hacker
hacker@paths~explicit-relative-paths-from-:~$ ../
ssh-entrypoint: ../: Is a directory
hacker@paths~explicit-relative-paths-from-:~$ pwd
/home/hacker
hacker@paths~explicit-relative-paths-from-:~$ cd /..
hacker@paths~explicit-relative-paths-from-:/$ pwd
/
hacker@paths~explicit-relative-paths-from-:/$ challenge/run
Incorrect...
This challenge must be called with a relative path that explicitly starts with a `.`!
hacker@paths~explicit-relative-paths-from-:/$ /./challenge/run
Incorrect...
You invoked this challenge with an absolute path. This challenge needs a relative path!
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{0zmHBi7JdpqtL5v9X07AdtlZmBp.dBTN1QDL1EjN0czW}```

PROCESS: use pwd command to find out the directory user is in, then cd/.. to go back and get to / directory and then ./challenge/run invokes the path in relative way.
