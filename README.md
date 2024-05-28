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
