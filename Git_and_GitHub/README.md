# Git & GitHub

## Introduction
- Git is an open source version control software which allows you to keep track of all the changes made to a project. Find full documentation on [https://git-scm.com][git_documentation].
- GitHub is a collaboration website that interacts with Git.

## GitHub Workflow
### For projects you have write access to
1. Branching
2. Commits
3. Pull Request
4. Collaborate
5. Merge
### For projects you don't have write access to
1. Fork
2. GitHub flow
3. Pull Request

## Cloning
To clone (or copy) a remote repository down to your local machine.

## Most used Git commands (command line)
- `git clone`
- `git pull`
- `git branch`
- `git checkout`
- `git status`
- `git add`
- `git commit`
- `git push`

## Commit
- It is represented by an ID : a SHA-1 Hash.
- It stores a reduced version of a file and includes some metadata. These metadata provide information about :
  - who made the commit,
  - what time the commit was made,
  - the parent commit,
  - etc.

## 2-step Commit

                      git add                      git commit
Working Directory  \-\-\-\-\-\-\-\-\-\-\-\-\->  Staging Area  \-\-\-\-\-\-\-\-\-\-\-\-\-> History (log)

## Merging
There are 2 ways to do it:
- Remote merge (by opening a pull request), and
- Locally merge

## Merge Conflicts
It occurs when you try to merge together two branches on which a same file has been modified on both branches and at the same line.

## Rebasing
Be careful when rebasing. It changes the history. But, it can be useful to make your history more linear.

## Undoing Commits
`git revert` (the best way to do it)
`git reset`
`git commit-ammend` (to change a commit message)
`git cherry-pick`


[git_documentation]: https://git-scm.com

