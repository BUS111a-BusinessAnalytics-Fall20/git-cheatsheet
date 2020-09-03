# Git & Terminal Cheatsheet
This file will will teach you how to interact with Git through your terminal.

## Navigating through your terminal

There are four basic commands that you can use to navigate through your terminal.

1. `ls` - this command will tell you what files and folders are in your current directory
1. `pwd` - this command will tell you what directory you are currently in
1. `cd <folder-name>` - this command will let you navigate down into a directory
1. `cd ..` - this command will navigate you up one directory
1. `mkdir <folder-name>` - creates a new folder in your current path

## Git Commands

There are several commands that you can use in the terminal to help you with Git.
Git is complicated to navigate using the terminal, so it is recommended that you
use a GUI (graphical user interface) such as [Github Desktop](https://desktop.github.com/)
to interact with Git repositories.

A nice cheat sheet for Git commands can be found [here](https://education.github.com/git-cheat-sheet-education.pdf).

However, here are a few commands that are good to know:

1. `git clone <repository-name>` - retrieve an entire repository from a hosted location via URL
1. `git init` - initialize an existing directory as a Git repository
1. `git status` - shows you what files have been modified, added, or deleted
1. `git add .` - adds all of your changed files to your staging environment
1. `git commit -m "This is my commit message"` - adds a commit message to your staging environment so people know what you did
1. `git push` - this pushes all code that is staged to your remote repository
