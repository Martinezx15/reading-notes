# **Revision of the cloud**
        
## What is Git?**
Git is distributed version control software. Version control is a way to save changes over time without overwriting previous versions. Being distributed means that every developer working with a Git repository has a copy of that entire repository - every commit, every branch, every file. If you're used to working with centralized version control systems, this is a big difference!
Whether or not you've worked with version control before, there are a few things you should know before getting started with Git:
 
## **Why Use Git?**
Version control is very important - without it, you risk losing your work. With Git, you can make a "commit", or a save point, as often as you'd like. You can also go back to previous commits. This takes the pressure off of you while you're working. Commit often and commit early, and you'll never have that gut sinking feeling of overwriting or losing changes.
There are many version control systems out there - but Git has some major advantages.
- Speed
- Merge conflicts
- Cheap branches
- Ease of roll back
  
## **Getting Started With Git** 
 Depending on your operating system, you may already have Git installed. But, getting started means more than having the software! To get started, it's important to know the basics of how Git works. You may choose to do the actual work within a terminal, an app like GitHub Desktop, or through GitHub.com. (Note: while you can interact with Git through GitHub.com, your experience may be limited. Many local tools can give you access to the most widely used Git functionalities, though only the terminal will give you access to them all.)
 

 ## **Learning & Mastering Git Commands**
- git clone [url]: Clone (download) a repository that already exists on GitHub, including all of the files, branches, and commits.
- git status: Always a good idea, this command shows you what branch you're on, what files are in the working or staging directory, and any other important information.
- git branch: This shows the existing branches in your local repository. You can also use git branch [banch-name] to create a branch from your current location, or git branch --all to see all branches, both the local ones on your machine, and the remote tracking branches stored from the last git pull or git fetch from the remote.
- git checkout [branch-name]: Switches to the specified branch and updates the working directory.
- git add [file]: Snapshots the file in preparation for versioning, adding it to the staging area.
- git commit -m "descriptive message": Records file snapshots permanently in version history.
- git pull: Updates your current local working branch with all new commits from the corresponding remote branch on GitHub. git pull is a combination of git fetch and git merge.
- git push: Uploads all local branch commits to the remote.
- git log: Browse and inspect the evolution of project files.
- git remote -v: Show the associated remote repositories and their stored name, like origin.
  
  ## **Things I want to know more about**
- Benefits of Git
- Most Common Git Commands
