git init
git add .
git commit -m "initial commit full reposatory"

<== Git config global ==> 
git config --list  [for check is git config ]
git config --global user.email "hm91hassan@gmail.com"
git config --global user.name "Mohammad Hasan"
<== Git config global ==> 


git remote add origin https://luovaltd@bitbucket.org/luovaltd/pourashava.git
first time ==>git push -u origin master
every time ==>git push origin master

<== com for remove orgin==> 
git remote rm origin



<==== Working command ===========>
git add.
git commint -m"commint details"
git push

<== pull ==>
git stash
git stash drop
git pull
<== pull  ==>


<== check status ==>
git status
<== check status ==>


<== check status ==>
git branch  [check branch list and your branch name]
git branch developer [create new "dev"]
git push --set-upstream origin 1.0 developer [New branch push online orgin "dev"]
git checkout developer [switch branch ]
git merge dev [git marge with "dev" branch]
<== check status ==>

<== Add git Tag ==>
git add .
git tag v1.0.0
git commit -m"publish v1"
git push --tag
<== Add git Tag ==>
