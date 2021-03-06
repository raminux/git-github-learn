# What are Git Repos?
A git **Repo** is a workspace which tracks and manages files withing a directory.  

# Git status
The following command gives information on the current status of a git repo and its contents:
```bash
$> git status
```

# Git init
Use the following command to create a new git repo. Before we can do anything git-related, we must initialize  a repo first:
```bash
$> git init
```

# Understanding .git directory
After issuing the `git init` command, a hidden directory called `.git` is created which holds all the `git` related stuffs. 
> Before running `git init`, use `git status` to verify that you are not currently inside a repo. 

- One repo per project!

# Git commit
This is the most important git feature, i.e. the butter and bread of git. A commit is a check-point in time, an snapshot of the project at that time. To commit changes, use the following git command
```bash
$> git commit -m "header changed"
```
As you can see, we can add some comment to the commit. It should be noted that the commit message must summarize the changes in the commit. It is of utmost importance to know what to write here. As we're going further, we'll learn how to do that. 
> Issuing `git commit` command without the `-m` flag will show you a box to enter your message. 

# Git add
To mark files to be commited, use `git add` command and specify the files you want:
```bash
$> git add navbar.css navbar.html
$> git add navbar.js
```

In terms of git language, the `git add` command adds files to the staging area. 


# Git commiting workflow
The below diagram shows the basic workflow of git commit:
```mermaid
graph LR;
    WD["Working Directory"]--  git add .->SA["Staging Area"];
    SA-- git commit .-> Repository
```

# Git log 
The following command return the commit history of the repository
```bash
$> git log
```
 







