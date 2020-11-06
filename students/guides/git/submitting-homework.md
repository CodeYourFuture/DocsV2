---
id: submitting-homework
title: Submitting Homework (Github Desktop)
---

## Why fork

For many of the CodeYourFuture homework assignments,
you will need to make a Pull Request to a GitHub repository.
By default GitHub repos prevent most people from pushing to them.
This is ensure that repo owners have control over the project.

This doesn't mean you will never be able to make changes to the repo!
On GitHub you do this by creating a "fork".
A fork is an exact copy of the original repo but copied to your own GitHub account.
This means that now you can push to it!

This is why you will need to create a fork when submitting a PR for your homework.

## What is a remote

Git has a concept of a "remote".
These are other git repositories that can be connected to over the internet.
You can push or pull code changes from them.
Remotes have a _name_ and a _URL_.
Most of the remotes that you will use at CYF are hosted on GitHub,
so have a github.com URL.

When you clone a repo from GitHub, the default remote is named `origin`
and the URL is set to that of the GitHub repo.

You can view the remotes you have set up with:

```bash
git remote -v
```

## How to fork a GitHub repo

Firstly you need to click the "Fork" button:

![Fork Button](assets/making-a-pull-request/fork-button.png)

Then you should be brought to your new fork (notice how the repo title changes):

![Forked repo](assets/making-a-pull-request/forked.png)

Now you can clone from your fork by clicking 'Open in Github Desktop'

![Clone from fork](assets/making-a-pull-request/clone-fork.png)

## Creating a Branch

In order to be able to submit you work you must do all of your homework on a branch.

You can create a branch in Github Desktop by clicking here

![Create Branch in Github Desktop](assets/making-a-pull-request/pr_github_desktop.png)

You should then give your branch a sensible name

![Create Branch in Github Desktop](assets/making-a-pull-request/name_branch_github_desktop.png)

## Creating a PR

So you've done your homework.
You've committed your changes and are ready to make a PR.
Congrats! 🎉🎉🎉

At this point you should have followed the instructions either to
[fork the original repo](#how-to-fork-a-github-repo) or
[added a remote to your fork](#adding-a-remote).
If you haven't make sure you read those sections first.

You will need to push to your fork.
If you forked and then cloned
(as in the [how to fork instructions](#how-to-fork-a-github-repo))
then you just need to run `push`.

Next you need to go the original repo in your browser
(probably starting with <https://github.com/CodeYourFuture)>. **It is important that you open a pull request against the original repository.**

Next click the button that says `Compare & Pull Request`:

![PR tab](assets/making-a-pull-request/pull_request_compare.png)

Almost there! Now fill out the PR form.
Give it a sensible title and an (optional) description:

![PR form](assets/making-a-pull-request/pr-form.png)

And finally click the Create pull request button at the bottom of the form:

![Create pull request](assets/making-a-pull-request/create-pull-request-2.png)

That's it! You created your PR!

![Created PR](assets/making-a-pull-request/created-pr.png)

## Resources

- [Creating a pull request from a fork](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork)
