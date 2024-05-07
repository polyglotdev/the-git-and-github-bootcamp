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

```bash
.git
├── COMMIT_EDITMSG
├── FETCH_HEAD
├── HEAD
├── config
├── description
├── hooks
│   ├── applypatch-msg.sample
│   ├── commit-msg.sample
│   ├── fsmonitor-watchman.sample
│   ├── post-update.sample
│   ├── pre-applypatch.sample
│   ├── pre-commit.sample
│   ├── pre-merge-commit.sample
│   ├── pre-push.sample
│   ├── pre-rebase.sample
│   ├── pre-receive.sample
│   ├── prepare-commit-msg.sample
│   ├── push-to-checkout.sample
│   └── update.sample
├── index
├── info
│   └── exclude
├── logs
│   ├── HEAD
│   └── refs
│       ├── heads
│       │   └── main
│       └── remotes
│           └── origin
│               └── main
├── objects
│   ├── 04
│   │   └── 5449dd0eb650405ad7649aa3f435fab5c8f702
│   ├── 1b
│   │   └── 700323c9d00a71edd0697a418e2165632843a4
│   ├── 1c
│   │   └── 15dea28cae2887add5c42bab1f5210d2f8431b
│   ├── 21
│   │   └── e537da6174f93aeecb7e28d52bb6e1c0675c0b
│   ├── 24
│   │   └── f8ba726da031ed03c5b5e4fc01b83e90dc7f78
│   ├── 26
│   │   └── 1dee4b07a2e7b9821ab408a50fa596191eafcb
│   ├── 2a
│   │   └── c1dd7fb959d7a2ec4d9bf05dd104b92d0b28ea
│   ├── 2b
│   │   └── 1b3fac493252b25cdf742ab6a88dd08c8259d6
│   ├── 2c
│   │   └── 82db9217c2bbac0e37dbc6166b566777f6a0e2
│   ├── 3a
│   │   └── 951c759204f79dbe5427a1feff0cf8aedc5740
│   ├── 3d
│   │   └── a137a25a0e60f799b9c87f1d18e0a8783122bd
│   ├── 3e
│   │   └── c50995ca304c59f8efac0250ff089b9cf9934e
│   ├── 42
│   │   └── 061c01a1c70097d1e4579f29a5adf40abdec95
│   ├── 4e
│   │   └── ff036b831c93ec6683b394f8bb377976a0fe2d
│   ├── 51
│   │   └── 349d131d14305b6f2fa83514e723e8a80391a9
│   ├── 55
│   │   └── d138c8731453ec6475f55c9219e1e5c11fed1d
│   ├── 57
│   │   └── 034014ff08146e311a56fb98a4d2a589dd0686
│   ├── 59
│   │   └── 42a95a65d2812d19606b2b26363072a255c1aa
│   ├── 60
│   │   └── 1d706ddaf933f6299e7c753cda755d425e5f35
│   ├── 63
│   │   └── 9aebb82b8f1e8da8df6bd8a3e7ce0a9e576dbf
│   ├── 64
│   │   └── 8de5b335532c5a3602f6cf55f1a93e2aefa88f
│   ├── 65
│   │   └── 2049246a27a793fbd5afcfef939870c77feb38
│   ├── 6c
│   │   └── 0a8d6500feaf2190208c27f9e1b8576125a6fd
│   ├── 75
│   │   └── eb218b646602bdf7922c18444103595e944dd6
│   ├── 7c
│   │   └── 36b7510bd81fa8a2dca8bfe1a5949e1e420b6b
│   ├── 7f
│   │   └── 07d47c6a0648558b432f7fdcb0a4d3d6713b0e
│   ├── 80
│   │   └── 2b7c7d732454fe7d449c13dda31cf8fed15d2b
│   ├── 85
│   │   └── 0590cae2563f888d3146813164cf9c7d5ce54a
│   ├── 89
│   │   └── ed2993d9f57c5840c62053192555e323ab1276
│   ├── 8b
│   │   └── 825b64b8632fc8403a729c7f5856e8d82d1723
│   ├── 93
│   │   └── 2e7743742f156e3adbfaf20ea740f022817d84
│   ├── 9c
│   │   └── 1d175670d4d18778ada003e28d95ea9a02a538
│   ├── 9f
│   │   └── 2b76aa73d7900b7fb22f2e26504ae1fc72eca0
│   ├── a0
│   │   └── edc701f86c6fb4b8971ee001211d6ec6e01429
│   ├── a4
│   │   └── 85868adfd04585256763d965708938b20e31ef
│   ├── ac
│   │   └── 0e1fbdc40cd955e776f5aa33a4c509e492342b
│   ├── ae
│   │   └── dfc1f494dff627446483878a122c8f43d72cfd
│   ├── bd
│   │   └── 5298a821ecc1262e708a57da9261e1a89f837c
│   ├── c1
│   │   └── e92b9c6f2f81c564154cd702f9a735c0397e20
│   ├── c7
│   │   └── fcffe6a429813ef60b70b32e9afa10e257a523
│   ├── ca
│   │   └── aa338053fd6ad2f741acb4a2a99232740d883e
│   ├── d7
│   │   └── e40e7582a1d979d35d60b7fcca6d39baa6ca91
│   ├── de
│   │   └── 63aa764ff3ba86d432a694ee910c15ee57fa4b
│   ├── eb
│   │   └── 30d6f9117aa8e340e6e4141912631809c3be2c
│   ├── f3
│   │   └── ab90cdb842de3c6656084dfafa69be4b432ad7
│   ├── f6
│   │   └── 9767ac4aadd1133cb1ee9555a0facf33b50c9c
│   ├── fa
│   │   ├── 06f01f4fe0eabdb6e207afc4ef1ca55aa97429
│   │   └── 8dffd380613a4ce4a42cbc5f67c8acd107f270
│   ├── info
│   └── pack
└── refs
    ├── heads
    │   └── main
    ├── remotes
    │   └── origin
    │       └── main
    └── tags

63 directories, 73 files
```

## Commit Workflow

1. Make changes to your codebase
2. Add the changes to the staging area
3. Commit the changes to the repository
4. Repeat
5. Push the changes to a remote repository
6. Collaborate with other developers
7. Deploy your code to the web
8. Repeat

## Git Docs

[Git Docs](https://git-scm.com/doc)

The is a book called Pro Git that is available for free online. It is a great resource for learning Git. You can find it [here](https://git-scm.com/book/en/v2).
