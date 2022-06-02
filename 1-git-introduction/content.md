# What is Git?
It is the world's most popular version control system (VCS). VCS is a software that tracks and manages changes to files over time. Git is the most widely used VCS around the world. Actually, Git is a distributed VCS. 

# What can Git do?
Git is capable of hepling developers in the following categories:
- Track changes across multiple files
- Compare versions of a project
- "Time travel" back to old versions
- Revert to a previous version
- Collaborate and share changes
- Combine changes

# History of Git
Linux Torvals is the creator f Git. He decided to design git to overcome the difficulties and drawbacks of other exisiting VCSs when he was developing Linux. 

# Who uses Git?
Git users are diverse:
1. Engineers & Coders (==Git is a must-have skill for developers==)
2. Governments
3. Scientists
4. Writers
5. PhD Students
6. ...

# Git vs Github?
Git is a VCS that everyone can install and use it for tracking their own projects. Github is a service that hosts git repositories in the cloud and make it easier to collaborate with others. 

# Git Setup
Git is primarily a command-line tool, but there is also different GUIs to use as listed on `https://git-scm.com/`. 
```bash
$> sudo apt install git
$> sudo apt update
$> sudo apt install snapd
$> sudo snap install gitkraken --classic
```

# Configuring Git
After successful installation of Git, it is time to add your name and email to the git configuration. 
To check for the name and email, use the following command:
```bash
$> git config user.name
$> git config user.email
```
To configure a new name and email, use the following command:
```bash
$> git config --global user.name 'Ramin Esmzad'
$> git config --global user.email "ramin.esmzad@hotmail.com"
```
