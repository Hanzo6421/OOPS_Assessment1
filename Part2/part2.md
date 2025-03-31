# Part 2
## Questions 1
### 1. List three major version control software for software engineering

1. Centralized Version Control Systems
2. Distributed Version Control Systems
3. Popular Version Control Systems

## Questions 2
### 2.	What are the main advantages to using Git in your software development, and how is it useful for game developers.

<br>Git is an essential tool for managng projects that 
require a combination of coding, asset magement,
and team collaborattio. Its version control, 
branching, collaboration, and intedration
capabilities make it invaluable in maintaning the 
stability and quality of the project.

## Questions 3
### 3. Define the following terms in relation to Git. Branch, Pull, Push, repository, merge.

1. Branch: A separate line of development.
2. Pull: Fetches and integrates changes from a remote repository to your local copy.
3. Push: Uploads your local changes to the remote repository.
4. Repository: A storage location for all project files, along with their version history.
5. Merge: Integrates changes from one branch into another, typically from a feature branch into the main branch.

## Question 4
### 4.	If you are working at a company, which of their policies and procedures might relate to using version control systems such as Git.

1. Code Management Policies
2. Access Control and Security
3. Collaboration and Code review
4. Backup and Recovery
5. Compliance and Auditing

## Questions 5
### 5.	Merge conflicts can occur while using git. List merge tools or diff tools you can use to help you merge and deal with conflicts.

1. Meld
2. Araxis Merge
3. VS Code with GitLens

## Question 6
### 6.	In a merged source code file, how does Git let you know there is a conflict?

1. Conflict Markers
2. Conflict Notification
3. Status Check

## Question 7
### 7.	What are the steps you can take to resolve Git conflicts?

1. Identify the conflict
2. Open the conflicted file
3. Review the conflicting
4. Resolve the conflict
5. Test the changes
6. Stage the resolved file
7. Complete the merge
8. Push the changes

## Question 8
### 8.	What does git revert do, and how can you use it?

Git revert is a command used to undo changes by creating a new commit that reverses the changes introduced by a previous commit.

## Questions 9
### 9.	What does git reset do, and how can you use it? 

Git reset is a command used to undo changes in your working directory and staging area.

## Question 10
### 10.	What is the difference between git revert and git reset?

Git revert and git reset are both used to undo changes in Git,
but they serve different purposes. git revert creates a new commit 
that undoes the changes from a previous commit, preserving the commit 
history and making it safe for collaborative work. In contrast, git 
reset moves the HEAD pointer to a specified commit and can modify 
the staging area and working directory, potentially altering the 
commit history. 

## Question 11
### 11.	True or False: It is okay to commit broken code to the main branch.