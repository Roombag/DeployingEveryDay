# Day 4
This is day 4 of deploying every day and yesterday created a shell script to antomate copying my files to the server instead of typing all the commands by hand every time.
While this saved me about a minute every time I wanted to deploy my changes to the server, this also messed up everything when I accidentally pushed my unfinished code to the server.
So today I will start using Git as a version control system so I can roll back to a stable version of my code if I mess up and restore my server to a working state.
```
git config Name + Mail
git init
deploy.sh
```
Now every time I mess up I can go back to my last working commit i case I broke something.
Follow me to see how I improve my deployment tomorrow.
