# Unlock-Synoriq

## Learn TortoiseGit Tool for Git Operations
Playlist Link: [https://youtube.com/playlist?list=PLMJfvBwcOl66_1UJV8ywUoL7mZFPIMJKx](https://youtube.com/playlist?list=PLMJfvBwcOl66_1UJV8ywUoL7mZFPIMJKx)

1. [Tutorial 1 - How Git Works](#Tutorial-1)
2. [Tutorial 2 - How to clone git repository](#tutorial-2)
3. [Tutorial 3 - git add (staging) , commit and push](#Tutorial-3)
4. [Tutorial 4 - git fetch, merge and pull](#tutorial-4)
5. [Tutorial 5 - git branching(How to create branch in github, fetch it and push changes](#tutorial-5)
6. [Tutorial 6 - Merging branches (git merge) - Fast Forward vs 3-way merge](#tutorial-6)
7. [Tutorial 7 - Create, switch or delete branch using tortoisegit](#tutorial-7)
8. [Tutorial 8 - Stashing (save local changes) using tortoisegit](#tutorial-8)
9. [Tutorial 9(a) - Undoing local changes using tortoiseGit revert option](#tutorial-9a)
10. [Tutorial 9(b) - Undoing local changes using tortoiseGit reset option](#tutorial-9b)
11. [Tutorial 9(c) - git clean using tortoiseGit](#tutorial-9c)
12. [Tutorial 9(d) - git revert using tortoiseGit](#tutorial-9d)

#### Summary of Course
###### Tutorial 1
* Git is a Version Control System (VCS) as it manages Remote repository as well as Local Repository.
* Basic Git commands
> git add - Adds the file to the staging area which needs to update in the next commit.<br>
> git commit - Display all the changes and new files.<br>
> git push - Push all the commits to the remote repository.<br>
> git fetch - Fetch all the changes/files to the local repository from the remote repository.<br>
###### Tutorial 2
* Clone git reposittory means to download and use the repository from remote to local.
* Use tortoise git clone feature and copy HTTPS url from remote repository and use that url in tortoise git to clone the repository.
###### Tutorial 3
* Tortoise git is easy to use you have direct buttons to check status, do staging, do commit, or push files.
* While Pushing choose local repo branch, Remote repo branch, and Destination (Origin if you want to commit in same repo).
###### Tutorial 4
* Use tortoise git fetch option.
* Select remote branch/repository.
* The fetched file needs to be merged in a local branch.
###### Tutorial 5
* To create a new branch you need to be present in a master branch.
* Go to the branches write a branch name and click on create branch "branch name".
* While creating a new branch is always the same as the master branch at that time.
* After creating a new branch it will fetch a new branch too in the local repository.
* Use tortoise git switch/checkout to change the branch in the local repository.
* We also have an option to change the branch name while changing the branch.
* If you are using HTTPS it will ask for credentials but if you are working with SSH it will not ask for credentials.
###### Tutorial 6
* Use tortoisegit show log to check all the changes/commits. Select All Branches to see the log of all available branches in the repository.
* Change branch to that branch in which you have to merge another branch.
* use tortoisegit merge and select the branch name from where we need to merge the branch.
* by default it will do fast forward merge.
* In case of conflict we need to use tortoisegitmerge and solve that conflict manually.
###### Tutorial 7
* Use tortoisegit to create a branch and write the name of the branch. By default, it will create a new branch from the master but we have the option to change the base branch.
* Use tortoisegit switch/checkout to change the branch.
* Use tortoisegit browse references to and delete the branch you want to delete.
###### Tutorial 8
* Stash means storing something safely.
* Use tortoisegit stash save write meaningful message before saving it.
* Click on the include untracked option to perform an action with new files.
* Use stash pop to get back the last stashed files.
* Use stash list to check all the stashed. You can select the stash from there too.
###### Tutorial 9a
* Revert changes by using the tortoisegit revert option.
* select all files you need to get back.
###### Tutorial 9b
* Reset command `git reset --hard`
* It reverts all the local changes.
* This does not affect untracked files.
* This feature only works on commits.
###### Tutorial 9c
* Use reset feature in the last commit state.
* Choose Hard reset type.
* Do tortoisegit cleanup.
* Mark remove untracked directories and dry run.
###### Tutorial 9d
* Use reset feature in the last commit state.
* Choose Hard reset type.
* Do tortoisegit cleanup.
* Mark remove untracked directories and dry run.
