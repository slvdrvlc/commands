# Best git commands ⭐️

## Remember

1. Golden Rule, you can rewrite the history if you are the only one working on the project
2. Make clean, single-purpose commits
3. Write meaningful commit messages
4. Commit early, commit often
5. Don’t alter published history (group projects)
6. Don’t commit generated files

## Is between [] what we must change or add

## git config

configure user name

`git config --global user.name “[name]”`

configure user email

`git config --global user.email “[email address]”`

configure init

`git config --global init.defaultBranch [branch]`

## git init

initialize repository in current folder

`git init`

initialize repository in folder

`git init [repository folder name]`

## git clone

clone repository

`git clone [url] [optional name]`

## git remote

view remotes

`git remote -v`

add remote

`git remote add [variable name] [Remote Server Link]`

remove remote

`git remote rm [variable name]`

rename remote

`git remote rename [old variable name] [new variable name]`

changes an existing remote repository URL

`git remote set-url [variable name] [Remote Server Link]`

## git add

add file or folder to stage

`git add [file or folder/]`

add all files and folders to stage

`git add .`

## git commit

commit staged files

`git commit -m “[commit message]”`

add and commit files and folder with previous commit

`git commit -am “[commit message]”`

replace previus commit

`git commit --amend -m “[new commit message]”`

## git checkout

switch to commit/branch/tag

`git checkout [commit/branch/tag]`

create and switch to branch

`git checkout -b [branch name]`

restore projecto to previous commit

`git checkout .`

## git restore

restore file or folder to previous commit

`git restore [file or folder/]`

restore projecto to previous commit

`git restore .`

## git revert

revert changes of previous commit and create a new commit

`git revert HEAD`

## git reset

unstage file or folder

`git reset [file or folder/]`

unstage all changes

`git reset .`

reset to commit but changes are maintained

`git reset HEAD~[number of commits behind]`

reset to commit but changes are maintained

`git reset [commitID]`

reset all project to commit

`git reset --hard [commitID]`

## git tag

list tags

`git tag -l *[optional filter]*`

create tag in current commit

`git tag [tag name]`

create annotated tag in current commit

`git tag -a [tag name] -m "[tag message]"`

delete tag

`git tag -d [tag name]`

## git pull

fetch and merge changes from remote to local repository

`git pull [variable name] [branch]`

## git push

add remote-tracking reference

`git push -u [variable name] [branch]`

push branch to remote

`git push [variable name] [branch]`

push all branch to remote

`git push --all [variable name]`

delete remote branch

`git push [variable name] :[branch name]`

`git push [variable name] -d [branch name]`

push tag to remote

`git push origin [variable name] [tag name]`

force push

`git push -f`

## git branch

create branch

`git branch [branch name]`

delete local branch

`git branch -d [branch name]`

delete remote-tracking branch

`git branch -d -r [variable name/branch]`

## git merge

merge changes from branch to current branch

`git merge [branch name]`

merge changes to branch from branch

`git merge [branch name] [branch name]`

## git rebase

rebase to branch

`git rebase [branch]`

rebase from parent branch to child branch

`git rebase [parent branch] [child branch]`

interactive rebase

`git rebase -i HEAD~[number of commits behind]`

## git stash

stash uncommited changes with a message

`git stash save "[stash message]"`

re-apply stash

`git stash pop [stashID]`

view stash list

`git stash list`

delete stash

`git stash drop [stashID]`

## git cherry-pick

add an existing commit to the current branch

`git cherry-pick [commitID]`
