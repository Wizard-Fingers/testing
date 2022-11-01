This is a practice commit project that we are all working on

## How to contribute

open your command line and type: 

cd Desktop

then type:
mkdir practice project

then type:
cd practice project

then follow the instructions below

## Getting started

#1 go to the repo at: https://github.com/Bear1986/testing
from there fork it and make a copy of it on your own github account

#2 clone the repo to your local machine from your github account using the command line:

git clone (flowed by the url of your repo)

#3 then open the project in your favorite text editor (VS Code is the best) and open a terminal window and type:

git remote add myapp git://github.com/Bear1986/testing

(N.B this is the original repo that you forked from and not your own repo on github and you don't have to call it myapp you can call it whatever you want)

#4 then in vs code terminal add:
git checkout -b myapp 
(this will create a new branch called myapp)

#5 then make changes to the project and save them and then in the terminal type:

git add .
(this will add all the changes you made to the project to the staging area of git)

#6 then type:

git commit -m "your commit message here"
(this will commit the changes you made to the project to your local repo)

#7 then type:
git push
(this will push the changes you made to your local repo to your github repo)

#8 then go to your github repo and click on the compare and pull request button and then click on create pull request
