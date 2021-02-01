# Unlock-Synoriq

## Git and GitHub Beginner
Playlist Link: [https://youtube.com/playlist?list=PLhW3qG5bs-L8OlICbNX9u4MZ3rAt5c5GG](https://youtube.com/playlist?list=PLhW3qG5bs-L8OlICbNX9u4MZ3rAt5c5GG)

1. [Tutorial 1 - Introduction](#Tutorial-1)
2. [Tutorial 2 - Install Git (mac/Linux)](#Tutorial-2)
3. [Tutorial 3 - Install Git windows](#Tutorial-3)
4. [Tutorial 4 - Enable git commands autocomplete and colors on Mac/Linux](#Tutorial-4)
5. [Tutorial 5 - Branching and Merging](#Tutorial-5)

#### Summary of Course
###### Tutorial 1
* Git is a Distributed Version Control System. Very useful in Team Work. Easy to solve conflicts and keep all history. Also, it is open source.
* Github is a kind of cloud storage that keeps our repository. It also provides backup. It's a Graphical User Interface that's why it is easy to use for anyone.
* Git != Github
* Github, Tortoise Git, Visual Studio Code using GIT.
###### Tutorial 2
* Use the command `git --version` in the terminal to check whether git is installed in your OS (MAC/Linux) or not.
* Download git from [https://git-scm.com/downloads](https://git-scm.com/downloads) and read documentation for installation process [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
* Create your free GitHub account using [https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) link.
* Read this documentation to config your git [https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
* Use `git init` to initialize git.
* Use `git status` to get the states of a working folder and it will also tell you stagged and unstaged files.
* `git add filename` is used to know which file needs to be staged in the next commit.
* `git commit -m "commit message"` is used to do commits in the main repository
* `git remote add origin "repository git link"` used to know the commits need to be the push in origin.
* Push all your commits in the master branch using `git push -u origin master`
* Use `git --help` to see all available commands.
###### Tutorial 3
* Use the command `git --version` in the terminal to check whether git is installed in your OS (Windows) or not.
* Download git from [https://git-scm.com/downloads](https://git-scm.com/downloads) and read documentation for installation process [https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
* Create your free GitHub account using [https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) link.
* Read this documentation to config your git [https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
* Use `git init` to initialize git.
* Use `git status` to get the states of a working folder and it will also tell you stagged and unstaged files.
* `git add filename` is used to know which file needs to be staged in the next commit.
* `git commit -m "commit message"` is used to do commits in the main repository
* `git remote add origin "repository git link"` used to know the commits need to be the push in origin.
* Push all your commits in the master branch using `git push -u origin master`
* Use `git --help` to see all available commands.
###### Tutorial 4
* Use this command to put git-completion.bash script in your home directory `curl https://raw.githubusercontent.com/git/git/master/contrib/completion/git-completion.bash -o ~/.git-completion.bash`
* Use command `vi ~/.bash_profile` to edit .bash_profile file and add these lines
```
if [ -f ~/.git-completion.bash ]; then
  . ~/.git-completion.bash
fi
```
* `git config color.ui` is used to check wether coloring is on (true) or off (false)
* Use `git config --global color.ui true` to turn on coloring and `git config --global color.ui true` to turn of coloring.
###### Tutorial 5
* Branching is a very useful way to review whether the change is useful or not. Always preferred to make a different branch and do changes to it.
* create a new branch using `git branch "branch name"` and use `git checkout "branch name"` to switch branch.
* Let's merge new branch in master branch using `git merge "branch name need to merge in master"`.
* Need to use push command to check on github.
* Use `git branch -d "branch name"` to delete any branch. (You can't delete master branch).
