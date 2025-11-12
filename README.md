
Git Commands
============

    git init
------------
 Used to initialise a **new** Git repository

    git remote add origin <repository_url>
--------------------------------------
 Used to connect your **local** repository to a **remote** repository

    git branch -M main
--------------------------------------
 Used to create and switch to the **main** branch (-M stands for move/rename)

    git add "file_path" or git add . (to add all files)

First commit (" **.** " stands for all files, you can specify individual files instead)

    git commit -m 'Initial commit'
--------------------------------------
 Used to commit changes with a message (-m stands for message)

    git push -u origin main
--------------------------------------
 Used to push changes to the **remote** repository on the **main** branch (-u stands for upstream, sets the default remote branch for future pushes)
 
    git branch <branch_name>
--------------------------------------
 Used to create a new branch with the specified name

    git switch <branch_name>
--------------------------------------
 Used to switch to the specified branch

    git checkout -b <branch_name>
--------------------------------------
 Used to create and switch to the specified branch (-b stands for branch)

    git clone <link_to_repository>
----------------------------------
Used to create a copy of an existing repository locally

    git status
----------------------------------
Used to check the status of your files in the working directory and staging area

    git merge <branch_name>
----------------------------------
Used to merge changes from the specified branch into the current branch