# Git_Notes
For Reference Purpose

# Git
Git is a distributed version control system (VCS) used to track changes in code, collaborate with multiple developers, and manage projects efficiently. It was created by Linus Torvalds in 2005 for Linux kernel development but is now widely used for software development across various industries.<br>

# Git Bash
Git Bash is a command-line interface (CLI) for Git on Windows. It provides a Unix-like environment, allowing users to execute Git commands using a terminal that supports common Unix/Linux shell commands.<br>

# Cloning a Github Repository to your computer
Use the following command in command prompt or command line (if *git bash* is installed else install *git bash*)<br>
`git clone <repository link>`<br>

Example is `git clone https://github.com/mohammedfarhannp/Git_Notes.git`

# Updating Local Git Repository with new changes in the Github Repository.
Say you have a github repository in your computer and the owner of the repository adds new code or makes new commit, and you would like to update the Repository in your computer with the contents on github repository.<br>
<br>
Navigate to the location where `.git` folder exists and use the following command<br>
`git pull origin <branch-name>`<br>

Example be like : `git pull origin master` <br>
*This repository is in master branch*
