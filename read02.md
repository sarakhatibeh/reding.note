# Git


### Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it . Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

## Setting up a Git Repository
## Importing

1. Switch to the target project’s directory
2. Use the git init command
3. To start tracking these repository files, perform an initial commit by typing the following:

## Cloning
### You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:

$ git clone https://github.com/tes
### To clone a repository into a directory with another name of your choosing, use the following command format

 # work flow
[work flow](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

# The Life Cycle of File Status[
[life cycle](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

# Tracking and Staging a New File
### Single File

Track one file only by using the following format

git add filename

# All Files

Track all files in a repository by using the following command
$ git add *

## Pushing Changes
### Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of pushing changes to remotes.

Example:

$ git push origin master







