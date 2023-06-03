## Git Continuation
* Create a new folder called as cicd (anywhere in your system)
* initialize the repository
* create the following folders and add Readme.md in each folder
    * git
    * maven
    * msbuild
    * sonarqube
    * artifactory
    * jenkins
    * azuredevops

* Now commit these changes
* Now edit Readme.md in git and try to write one line about git (google and write) commit these changes
* Now make the the change in each folder’s Readme.md as one commit

![Preview](./Images/git-1.png)

![Preview](./Images/git-2.png)

* Now repeat the above by changing readme.md of each tool with one line description and commit it.

## Next Steps:
* Selective addition to staging area.
* Removing the changes from staging area
* Removing the changes from working tree
* Modifying commits.

* Different States a file can be and actions that transition between them

![Preview](./Images/git22.png)

* Areas of git w.r.t local repository

![Preview](./Images/git7.png)

* Current Status:

![Preview](./Images/git-3.png)

* Add all the changes into staging area ``` git add --help ```
* Add only modified files to the staging area

![Preview](./Images/git-4.png)

![Preview](./Images/git-5.png)

* Adding files with some pattern

![Preview](./Images/git-6.png)

![Preview](./Images/git-7.png)

* Other example

![Preview](./Images/git-8.png)

![Preview](./Images/git-9.png)

## Moving changes from Staged Area back to working tree

* Add the changes to the staging area

![Preview](./Images/git-10.png)

* Now remove one file from staging area (unstage)

![Preview](./Images/git-11.png)

* To move the file from modified state in working tree to unmodified

![Preview](./Images/git-12.png)

* To move the changes from staging area to unmodified state

![Preview](./Images/git-13.png)

* Git reset is the old command and to move the changes from staging area to working tree the following was the approach

![Preview](./Images/git-14.png)

![Preview](./Images/git-15.png)

* Untracked files add to the staging area

![Preview](./Images/git-16.png)

* Moving them back to working tree

![Preview](./Images/git-17.png)

* To remove the untracked files from worktree we have ``` git clean ```

![Preview](./Images/git-18.png)

* If you have directories as part of your untracked files

![Preview](./Images/git-19.png)

## Exercises
* Try to findout what git reset --soft, git reset --hard does?
* Findout what git revert does ?
* Findout what git rm does ?


