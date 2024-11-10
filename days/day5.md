# Day 5
This is day 5 of deploying every day. Yesterday I started using Git so I can roll back my project in case I mess up while working on it but it got kind of impractical haveing to roll back to a 
working version if I broke the server so today I will create a develpoment branch in my Git repository where I can break the code all day long while the main/master branch stays stable.
```
git branch dev
git checkout dev
*code*
git commit ...
git checkout?/Switch main
deploy.sh
```
