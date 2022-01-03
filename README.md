# Git-Commands
## Git Config Commands
This command sets the autor name and email address to be used with your commits.
Command:
$ git config --global user.name "Kanchan"
$ git config --global user.email "test123@gmail.com"

## Git init Commands
This command is used to create local repository.The init command will initialize an empty repository.
Command:
$ git init Demo

## Git Clone Commands
This command is used to make a copy of repository from an existing URL.
Command:
$ git clone URL

## Git add Commands
This command is used to add one or more file to staging(index) area.
Command:
To add one file:
$ git add fileName
To add more than one file:
$ git add *

## Git commit Commands
Commit command is used in two scenarios. They are as follows.
Command:
$ git commit -m "commitMessage"
This command changes the head. It records the file permanently in the version history with a message.
$ git commit -a 
This command commits any file added in the repository with git add and also commits any files you've changed since then.
e.g. git commit -a -m 'integration added'

## Git status Commands
The status command is used to display the state of the working directory and the staging area.
Command:
$ git status

## Git push Commands
Command:
$ git push origin master
This command sends the changes made on the master branch, to your remote repository.
$ git push -all
This command pushes all the branches to the server repository.

## Git pull Command
Pull command is used to receive data from GitHub. It fetches and merges changes on the remote server to your working directory.
Command:
$ git pull URL

## Git brancg Command
This command lists all the branches available in the repository.
Command:
$ git branch

## Git merge Command
This command is used to merge the specified branch?s history into the current branch.
Command:
$ git merge branchName

## Git log Command
This command is used to check the commit history.
Command:
$ git log

By default, if no argument passed, Git log shows the most recent commits first. We can limit the number of log entries displayed by passing a number as an option, such as -3 to show only the last three entries.
$ git log -3

## Git remote Command
Git Remote command is used to connect your local repository to the remote server. This command allows you to create, view, and delete connections to other repositories. These connections are more like bookmarks rather than direct links into other repositories. This command doesn't provide real-time access to repositories.
Command:
$ git remote add origin URL

## Staging & Commits
## Undoing Changes
## Inspecting Changes
## Branching & Merging
## Collaborating
