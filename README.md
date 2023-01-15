# git-cmds
A small guide to most used git cmds

`$ git config --global user.name "Danny Adams"`

`$ git config --global user.email "myemail@gmail.com"`

`$ git init <directory>`

`$ git clone <url>`

`$ git add <file>`

`$ git add .`

`$ git commit -m "commit message"`

```
main: default development branch
origin: default upstream repo
HEAD: current branch
HEAD^: parent of HEAD
HEAD~4: great-great grandparent of HEAD
```

`$ git branch`

`$ git branch <new-branch>`

`$ git checkout <branch>`

`$ git checkout -b <newbranch>`

`$ git branch -D <branch>`

```
 $ git checkout b
 $ git merge a
```

`$ git merge --squash a`

```
$ git checkout feature

$ git rebase main
```

```
$ git remote add <alias> <url>
```

```
git checkout main
git pull
git checkout my-feature-branch
git merge main
```
```
git checkout main
git pull upstream main
git checkout my-feature-branch
git rebase main
```
 
