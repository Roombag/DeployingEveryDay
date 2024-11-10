# Day 3
> This will get split up into two episodes. One for the shell script and another for Git

This is day 3 of deploying every day and yesterday made an update to my code and copied it to the server using ssh and scp but today I thought I'd do something smart and I made a script for updating the code on my server which has the same commandy I used yesterday.
While this saved me about a minute every time I wanted to deploy my changes to the server, this also messed up everything when I accidentally pushed my unfinished code to the server.
So today I will start using Git as a version control system so I can roll back to a stable version of my code if I mess up and restore my server to a working state.
```
git config Name + Mail
git init
deploy.sh
```
Now every time I mess up I can go back to my last working commit i case I broke something.
Follow me to see how I improve my deployment tomorrow.
