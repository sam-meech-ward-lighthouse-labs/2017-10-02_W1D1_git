# Git

Version Control System

Tracks changes to text files.

## The Good

* Incredibly powerful, works for all kinds of different files.
* REally really fast. 
* Distributed. 
* many more

## The bad

* It's confusing to use. 
* Steep learning curve, and just a million features.

## The Workflow

* Do something, create a file, write some code, etc.
* `git add file` which tells git that we want to track changes to this file.
* `git commit -m ""` commits all the changes that were added into git. 

git add
git commit
git status

All local commands, all only on my laptop. Not github.

## Commit Messages

Just write a commit message. Doesn't matter how you write it, just write something meaningful.

Commit frequently, you can't over commit.

## Branching

* By default we get a master branch

`git branch branchname` will create a new branch
`git checkout branchname` will switch you to that branch

When you're happy with your changes and it's time to merge the code back to master:

* `git checkout master` checkout the branch that you're going to merge the code onto.
* `git merge featureBranch` will merge all code from featureBranch to master. 

Once we're done with a branch, `git branch -d featureBranch`

if master has changes that your feature branch doesn't have. `get merge master` onto that feature branch.

## Remotes

* Any repo not on your laptop. most of the time, this is github.

`git push`
`git pull`
`git remote`

push and pull are just merges with remote repos

## Forking

Will create a copy of someone elses repo on github into your account so you can make changes and commit and push them.

## For you guys

* Create a new xcode project and check the git checkbox.
* Create a new repo on github and push your code.
* Create a new feature branch and check it out.
* Modify code, add and commit code all on this feature branch.
* You can even push this branch.
* Once your feature branch is done, or good enough. Merge it into master.
* push master
* submit assignment.
* Work on stretch goals on another feature branch.

## Cheat Sheet

<https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf>