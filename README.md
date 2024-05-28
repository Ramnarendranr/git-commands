# git-commands


**git init**
    
        Description: Initializes a new Git repository in the current directory. This command sets up the necessary files and directories for version control.
    
        Example: git init
    
        This command creates a new .git directory in your current working directory, marking it as a Git repository.

**git pull**

        Description: Fetches changes from a remote repository and merges them into the current branch.

        Example: git pull origin main

        This command fetches updates from the main branch of the origin remote repository and merges them into your current branch.

**git push**
        Description: Uploads local repository content to a remote repository. Pushes commits from your local repository to a remote repository.

        Example: git push origin main

        This command pushes your local commits to the main branch of the origin remote repository.

**git merge**

        Description: Merges changes from one branch into the current branch. Creates a merge commit that combines the changes.

        Example: 
            git checkout main
            
            git merge feature-branch

        This merges the feature-branch into the main branch, creating a merge commit.

**git add**

        Description: Adds changes in the working directory to the staging area.

        Example: git add .

        This stages all changes (new/modified/deleted files) in the current directory for the next commit.

**git commit**

        Description: Records changes to the repository. Creates a new commit containing the current contents of the staging area.

        Example: git commit -m "Add new feature"

        This commits the staged changes with the message "Add new feature".

**git revert**

        Description: Creates a new commit that undoes the changes from a previous commit.

        Example: git revert <commit-hash>

        This command creates a new commit that reverses the changes introduced by the specified commit.

**git stash**

        Description: Temporarily saves changes in the working directory that are not yet ready to be committed. Useful for cleaning the working directory.

        Example: git stash

        This stashes your current changes and restores a clean working directory.

**git clone**

        Description: Creates a copy of an existing Git repository. Downloads the repository and its entire history.

        Example: git clone https://github.com/user/repo.git

        This clones the repository from the specified URL to your local machine.

**git rebase**

        Description: Reapplies commits on top of another base tip. Useful for maintaining a clean, linear history.

        Example:
                git checkout feature-branch
                git rebase main

        This rebases the feature-branch onto the main branch.

**git diff**

        Description: Shows the differences between changes in the working directory and the index or a commit.

        Example: git diff

        This shows the changes in the working directory that are not yet staged.

**git checkout**

        Description: Switches branches or restores working directory files. Can also create a new branch.

        Example: git checkout -b new-branch

        This creates and switches to a new branch named new-branch.

**git status**

        Description: Displays the state of the working directory and the staging area. Shows which changes have been staged, which haven't, and which files are not being tracked by Git.

        Example: git status

        This command shows the current status of the repository.

**git rm**

        Description: Removes files from the working directory and the index.

        Example: git rm file.txt

        This removes file.txt from the working directory and stages the deletion for the next commit.

**git branch**

        Description: Lists, creates, renames, and deletes branches.

        Example: git branch new-branch

        This creates a new branch named new-branch.

**git log**

        Description: Shows the commit history for the repository. Displays a list of commits in reverse chronological order.

        Example: git log

        This displays the commit history.

**git fetch**

        Description: Downloads objects and refs from another repository. Fetches updates from the remote repository but does not merge them.

        Example: git fetch origin

        This fetches changes from the origin remote repository.

**git remote add**

        Description: Adds a new remote repository.

        Example: git remote add origin https://github.com/user/repo.git

        This adds a new remote repository named origin.

**git mv**

        Description: Moves or renames a file, directory, or symlink.

        Example: git mv oldname.txt newname.txt

        This renames oldname.txt to newname.txt.

**git config**

        Description: Sets configuration values for Git. Can be used to configure user information, preferences, and behaviors.

        Example:
                git config --global user.name "Your Name"
                git config --global user.email "you@example.com"

        This sets the global username and email address for Git commits.