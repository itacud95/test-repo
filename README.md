
# Git commands

`git status`
```
Checks status of repository. 
Shows any modified files (red). 
Shows any committed files (green). 
```

`git add README.md`
```
Add file to be committed. 
```

`git commit -m 'Add git commands'`
```
Commit staged changes, with a commit message. 
```

`git push`
```
Pushes commit to origin (Github). 
```

`git reset --hard origin/main`
```
Delete all local changes and take what is on Github.
```

`git checkout -b feature`
```
Creates and checks out a new branch 'feature'. 
```

`git checkout main`
```
Change branch to main. 
```

`git rebase feature`
```
Take feature's commits and puts them after main's last commit. 
Can create a merge conflict. 
```

`git diff`
```
Show what has changed. 
```