# **Краткое руководство по GIT (Short manual)**
## _Локальный репозиторий_

__1. Git basics__
+ git init - *will create a new local GIT repository*
+ git clone - *is used to copy a repository*
+ git add - *add a file as it looks now to your next commit (stage)*
+ git commit - *will create a snapshot of the changes and save it to git directory*
+ git push - *push local changes to the original*

__2. Make and change__+ 
+ git status - *list new or modified files not yet committed*
+ git diff - *lists down changes and conflicts*
+ git add [file] - *stages the file, ready for commit*
+ git reset [file] - *unstages file, keeping the file changes*
+ git commit -m"[discriptive message]" - *commit all stages files to versioned history*

__3. Git branching and merging__
+ git branch - *will list you branches*
+ git checkout - *switch to another branch and check it out into your working directory*
+ git merge - *will merge the specified branches history into the current branch*
+ git log - *show all commits inthe current branch's history*

__4. Synchronize__
+ git remote add <name> <url> - *create new connection to a remote repo*
+ git fetch - *get all the changes from the origin (no merge)*
+ git pull - *get all the latest changes from the origin and merge*
+ git push - *is used to upload your local repository changes to hte origin remote repo*

##**Работа с ветками**