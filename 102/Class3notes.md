
 # Class 03 Revisions and the Cloud

## Resources

1. [Git Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Version Control

- By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.
- Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

## Local Version Control

- A Local VCS entails one database on your hard disk that stores changes to files.

## Centralized Version Control

- **single** server storing all changes and file versions, which can be accessed by various clients.
- collaboration within a developer team on a single file or set of files
- streamlined the collaboration process
- Admin control over divvying up revision privileges.
- More knowledge of team members’ activities with certain files
- CVS goes down, collaborators cannot work with each other on a file or save changes and new versions
- corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.

## Distributed Version Control

- addresses the major vulnerability of the CVS
- DVCS allows clients to create mirrored repositories
- DVCS allows for multiple mirrored repositories
- Programmers can collaborate in various ways to complete a joint project, which enables the use of various simultaneous workflows.

## Snapshot

- save a changed version of your project — called commit — Git creates a snapshot of the file and stores
- git commit -m'message'

## Local Operations

- Git mostly relies on local operations
- eliminating the need to fetch history information from the server,
- Can work on a project without being online or on a vpn.

## Tracking Changes

- Git is gatekeeper and will track any changes made to a file or directory.
- Git will recognize any loss of information or file corruption.

## Loss of Data

- Git is designed to minimize the possibility of lost data or irreversible damage to data.
- Git makes it difficult for a snapshot of your file that is commited to be lost.

## Committed

- Files are secure in local data base

## Modified

- Files have been changed but not saved

## Staged

- Flags a files change to be committed in next snapshot

## History of Git

- Stems from Linux Kernal
- Origin in 2005, Git has become one of the most utilized Version Control Systems in the world.

## Getting Help

- git help command
- --help  command
- man git- command

## Setting up a Git Repository

- What is a git repository?

## Cloning

- create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.
- By cloning the file, you have copied all versions of all files for a project.
- To clone a repository into a directory with another name of your choosing add a new name after url. like: $ git clone https://github.com/test mydirectory

## Local Repository Structure

1. Working Directory: The actual files reside here.> Add .

2. Index: The area used for staging> git commit -m''

3. Head: Points to the most recent commit (Git commit lives here)

![Life cycle of file](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

## Committing a File

- git commit -m'message'
- After staging one or multiple files, you should commit the changes and record what you did within the commit message

## Git commit all changes
- git commit -a
- This command commits a snapshot of all modifications to tracked files in the working directory.
- **Dont Understand Following**:
- *This command pushes changes from the local “master” branch to the remote repository named “origin”.*

- *For cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local repository. However, these names can be changed by the user.*

# Sources
[GitTutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

## Things I want to know more about

- How to use git and learn shortcuts















