# ---git-commands---

Create new local repository. Erstellt ein lokales Repository:

````
$ git init [directory]
````
---
Creates local copy of remote repository

````
$ git clone [repo]
````
---
Stages specific [directory]

````
$ git add [directory]
````
---
Stages specific [file]

````
$ git add [file]
````
---
Commit everything that is staged.

````
$ git commit -m "[message]"
````
---
Shows status of changes as untracked, modified or staged

````
$ git status
````
---
Downloads all history from the remote branches

````
$ git fetch
````
---
Merges remote branch into current local branch.

````
$ git merge
````
---
Updates local working branch with all new commits from the corresponding remote branch. git pull is a combination of git fetch and git merge

````
$ git pull
````
---
Pushes all local branch commits to remote repository.
````
$ git push
````
