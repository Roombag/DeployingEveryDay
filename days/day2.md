# Day 2
This is day 2 of deploying every day and yesterday I set up my first server to run my project so my Service doesn't go down when I power off my computer.
Today I made a new version of my project and now I have to update my server but instead of putting my project on an USB-Stick to copy it to transfer it, today I will use SSH to connect to my server and update the code.
```
stop current process
ssh root@server
scp ...
go build
.\hello
```
