# git-master-class

## Version Control

- _Version control_, also known as _source control_, is the practice of tracking and managing changes to software code so that you can recall a specific version of it later.

## Difference between Git and GitHub

- Git is a distributed version control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files. Its goals include speed, data integrity, and support for distributed, non-linear workflows.
- GitHub is a web-based Git repository hosting service, which offers all of the distributed revision control and source code management (SCM) functionality of Git as well as adding its own features.

## Alternatives to Git

- Mecurial
- Perforce (Helix Core)
- Subversion

## Git Fetch and Git Pull

- git fetch is used to fetch changes from a remote repository without merging them into your local branch.
- git pull is used to fetch changes and automatically merge them into your current working branch.

## Git rebase

git rebase is a useful tool for cleaning up and organizing commit history, but it should be used with caution, especially on branches that have been shared with others.
'git rebase main' is the command for git rebase.

## Git cherrypick

git cherrypick is a Git command that enables you to implement a particular commit or a series of commits from one branch to another. It provides a method for choosing and implementing individual commits onto a branch without incorporating the entire branch's changes.

- git cherrypick <commit-hash> is the command for it. Here, <commit-hash> is the hash of the commit you want to apply.
