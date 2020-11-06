---
id: git-troubleshooting
title: Tips for Git issues 
---

We will be using GitHub to host the coding related homeworks and it is where you will be submitting, so it’s important you get used to this method and start to learn about the things that can go wrong and how you can fix them.

## Frequently Reoccurring Issues

### Creating git repos inside other git repos
Only use `git init` once in a project. If you’re using a folder from previous weeks, the git folder is already set up. When you go into another folder and then run `git init` in the terminal, you create a new git repo and now the computer has no idea what you’re trying to get to. Only use `git init` at the start of a new project.
 	
### Being on the incorrect branch

Please make use of commands like `git branch -a` which list both __local__ and __remote__ branches. __Local branches__ are branches on your personal machine whereas __remote branches__ are branches on GitHub.
You will see an asterix (*) next to the branch you’re currently on.

__Always make sure you are on the right branch before doing anything further!__

### Having the wrong remote

Remember to checkout what remote you are in with `git remote -v`. You will usually have an __origin__ remote. With other remotes, instead of doing `git pull origin master`, instead, it would need to be `git pull <remote name - that isn’t origin> master`.

In Git, __origin__ is a shorthand name for the remote repository that a project was originally cloned from.
