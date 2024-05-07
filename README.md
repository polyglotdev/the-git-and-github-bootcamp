# The Git and GitHub Bootcamp

[The Git and GitHub Bootcamp](https://www.udemy.com/course/git-and-github-bootcamp)

## Course Curriculum

- Intro
- Install
- Git Basics
- Committing in Detail
- Branching and Merging
- Diff and Merge Tools
- Stashing and Cleaning
- Undoing Things
- GitHub and Remotes
- Fetching and Pulling
- GitHub Odds and Ends
- Collaboration Workflow
- Rebasing
- Interactive Rebase
- Git Tags
- Git Behind the Scenes
- Reflogs
- Custom Aliases

## Section 2

[Link to Section 2 artifacts](https://www.canva.com/design/DAEQbZDcRTs/eoJbTLVE8BolmKIyFjGByQ/view?utm_content=DAEQbZDcRTs&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## What is Git?

Git is a distributed version control system that allows you to track changes in your codebase, revert to previous stages, work on different branches, and collaborate with other developers.

[Git](https://git-scm.com/)

## Visualizing Git

[Visualizing Git](https://git-school.github.io/visualizing-git/)

Git helps us:

- track changes
- collaborate with others
- work on different branches
- revert to previous stages
- and much more

## Git History

- Git was created by Linus Torvalds in 2005
- It was created to manage the Linux kernel
- It is now the most popular version control system in the world
- It is open source and free

## Git Installation

[Git Installation](https://git-scm.com/downloads)

## Git Configuration

```bash
git config --global user.name "Your Name"
git config --global user.email """
```

[Install GitKraken](https://www.gitkraken.com/)

## Behind The Name

Torvalds referred to Git as the "stupid content tracker" and the name "Git" is a British slang term for "unpleasant person".

The official Git source code explains a couple different meanings for the name, depending on your mood:

- random three-letter combination that is pronounceable, and not actually meaningful
- "global information tracker": you're in a good mood, and it actually works for you. Angels sing, and a light suddenly fills the room
- stupid. contemptible and despicable. simple.
- *God damn idiotic truckload of sh*t\*

## Git != GitHub

Git is a version control system that allows you to track changes in your codebase, collaborate with other developers, and revert to previous stages. GitHub is a platform that allows you to store your Git repositories in the cloud, collaborate with other developers, and deploy your code to the web.

## Repositories

A repository is a folder that contains your project files. It is where you store your codebase, track changes, and collaborate with other developers.

## Commands

- `git init` - initializes a new Git repository
- `git status` - shows the status of your repository
- `git add` - adds files to the staging area
- `git commit` - commits files to the repository
- `git log` - shows the commit history
- `git checkout` - switches branches
- `git branch` - shows the branches in your repository
- `git merge` - merges branches together
- `git push` - pushes changes to a remote repository
- `git pull` - pulls changes from a remote repository
- `git clone` - clones a repository from a remote server
- `git remote` - shows the remote repositories
- `git fetch` - fetches changes from a remote repository
- `git diff` - shows the differences between commits
- `git stash` - stashes changes in the working directory
- `git clean` - cleans untracked files from the working directory
- `git reset` - resets the repository to a previous state
- `git revert` - reverts a commit
- `git rebase` - rebases a branch onto another branch
- `git tag` - tags a commit
- `git reflog` - shows the reflog
- `git config` - shows the configuration settings
- `git remote add` - adds a remote repository
- `git remote remove` - removes a remote repository
- `git remote rename` - renames a remote repository
- `git remote set-url` - sets the URL of a remote repository
- `git remote show` - shows information about a remote repository
- `git remote prune` - prunes stale remote-tracking branches
- `git remote update` - updates the remote-tracking branches
- `git remote set-head` - sets the default branch of a remote repository
- `git remote set-branches` - sets the branches to be fetched from a remote repository
- `git remote set-url` - sets the URL of a remote repository
- `git remote set-url --push` - sets the push URL of a remote repository

## Mysterious `.git` Folder

The `.git` folder is where Git stores all the information about your repository, including the commit history, branches, tags, and configuration settings. It is hidden by default, but you can view it by running `ls -a` in the terminal.

