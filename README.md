# Bash and Git/Github

## Git
- git init: initialises git repository
- git status: shows status of current repositories, untracked files and tracked changes
- git add <File>: Adds file to repository (use . for all files in directory)
- git commit -m '': Confirms file as the latest update to the repository with an explanatory comment
- git remote --v: lists current connected remote repositories (e.g. are you connected to github)
- git log: shows log of all commits in current repository
- git push -u <remote name> <branch name>: pushes commits to the remote repository

### SSH
- Used to allow seamless pushes to remote repository
  - generate an ssh key through terminal
  - set up generated public key with remote repository (Github)

## Bash
- pwd: shows current directory (where you are)
- ls: shows all files in current directory (not hidden)
  - ls -a: shows all files in current directory including hidden files
- ll: shows long list with more detail of files in current directory
- cd <path>: changes current directory
  - path = ..: goes back one
  - path = ~: goes home
  - path = /: goes to root
- mkdir <path>: creates file directory
- touch <file>: creates file
- rm <file>: permanently remove file
  - -rf <dir>: remove directory
- cat <File>: read file
