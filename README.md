# Full Git Knowledge
## git configuration
```
git config --global user.name 'username'
```
```
git config --gloabal user.email 'useremail'
```
## list configuration
```
git config --list
```
## clone a repo (auto add git init)
```
git clone <repo-link>
```
## check staged file
```
git status
```
## add staged file
```
git add <file-name>
```
```
git add .
```
## commit file
```
git commit -m 'message'
```
## log
```
git log
```
```
git log --oneline
```
## push file
```
git push origin main
```
```
git push -u origin main
```
## create a git repo
```
git init    
```
## connect remote to local
```
git remote add origin <github-link>
```
## verify remote
```
git remote -v
```
## rename remote alias(name)
```
git remote rename <old-name> <new-name>
```
## remote url-check
```
git remote get-url origin
```
## pull
```
git pull origin <branch-name>
```
```
git pull
```
## branch check
```
git branch
```
## create new branch
```
git branch <new-branch>
```
```
git checkout -b <new-branch>
```
```
git switch -c <new-branch>
```
## branch navigation
```
git checkout <branch-name>
```
```
git switch <branch-name>
```
## rename branch name
```
git branch -m <new-branch-name>
```
```
git branch -m old-name new-name
```
## delete a branch
```
git branch -d <branch-name>
```
## force delete a branch
```
git branch -D <branch-name>
```
## delete branch from github
```
git push origin --delete branch-name
```
## stash
```
git stash
```
```
git stash apply
```
```
git stash drop
```
```
git stash pop
```
```
git stash list
```
```
git stash clear
```
## tag
```
git tag
```
```
git tag <version-name>
```
```
git tag -a <version-name> -m 'message'
```
```
git tag -a <version-name> <commit-hash> -m 'message'
```
## amend ( change commit name)
```
git commit --amend
```
```
git commit --amend -m 'message'
```