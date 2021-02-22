# add, commit, push cycle on on GitHub
## add files
* You will use the add and commit functions to add and commit changes that you make to git.

    - git add: takes a modified file in your working directory and places the modified version in a staging area.

    - git commit takes everything from the staging area and makes a permanent snapshot of the current state of your repository that is associated with a unique identifier.
    
**These two commands make up the bulk of many workflows that use git for version control**


![gac](https://www.earthdatascience.org/images/earth-analytics/git-version-control/git-add-commit.png)

* You can add an individual file or groups of files to git tracking. To add a single file, use

    - git add file-name-here-with-extension

* To add the README.md file that you just modified, you’d use:

    - git add README.md

* To add ALL of the files that you have edited at the same time, you can use:

    - git add --all

## Commit files
* Once you are ready to make a snapshot of the current state of your repository, you can use git commit. The git commit command requires a commit message that describes the snapshot / changes that you made in that commit.

* A *commit* message should outline what changed and why. These messages

    1. help collaborators and your future self understand what was changed and why 
    2. allow you and your collaborators to find (and undo if necessary) changes that were previously made.

* If you are not committing a lot of changes, you can create a short one line commit message using the -m flag: 
    - git commit -m "Editing the README to try out git add/commit"

* Alternatively, if you are committing many changes, or a small number of changes that require explanation, you’ll want to write a detailed multi-line commit message using a text editor.

* If you have configured git to use your favorite text editor (via git config --global core.editor your-fav-editor-here), then you can open that editor to write your commit message using the git commit command:

    - git commit

* Once you save your commit message and exit the text editor, the file that you created will contain your commit message.

# Push changes to GitHub

* So far we have only modified our local copy of the repository. To add the changes to your git repo files on your computer to the version of your repository on GitHub, you need to push them GitHub.

    - You can push your changes to GitHub with:

    git push

*You will then be prompted for your GitHub user name and password. After you’ve pushed your commits, visit your repository on GitHub and notice that your changes are reflected there, and also that you have access to the full commit history for your repository!*

## Remember For each change, practice using

    - git add to stage the change, and
    - git commit to take a snapshot of your repository
