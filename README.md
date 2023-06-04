# Git
Git Quick Notes


Global UserName:
$ git config --global user.name “<Enter your username here>”

Global Email Address
$ git config --global user.email “<Enter your email here>”

Initializing Git:
$ git init

Staging files/Adding files to Git repo :-
$ git add <filename with extension>

Staging all files in a folder :-
$ git add --all
or
$ git add -A

Making a Commit :-
$ git commit -m “<Enter your message here>”

Git Commit without Stage :-
$ git commit -a -m “<Enter your message here>”

Status of files and log
$ git status

File status in a more compact way :-
$ git status --short


Log is used to view the history of commits for a repo.
$ git log
$ git log --oneline

Git Help :- options for commands
$ git <command> -help

See all possible commands -
$ git help --all

Making a new Git Branch :
$ git branch <name of branch>

Checking all available Branches :-
$ git branch

Switching to other Branches :-
$ git checkout <branch name>



Making a new branch and directly switching to it :-
$ git checkout -b <branch name>

Deleting a Branch :-
$ git branch -d <branch name>

Merging two Branches :-
$ git merge <branch name>


Create a repo on https://github.com/youraccountname


Adding local repo to Github:
$ git remote add origin <paste copied URL here>


Push master branch to URL:
$ git push --set-upstream origin master



First commit all the changes. Then push all the changes to our 
remote origin i.e. remote repo on github.
$ git push origin


Git pull is used to pull all changes from a remote repository into the 
branch we are working on. It is a combination of fetch and merge. Use it 
to update your local Git.

$ git pull origin


Pull branch from GitHub :- 
$ git branch -a


For viewing only remote branches :-
$ git branch -r



Push branch to GitHub :-
First, let’s create a new local branch which we will be pushing to Github.
 
 Enter the command as ‘git checkout -b <branch name>’. 
 
 You can check the status of the files in this current branch using ‘git status’. 

Commit all the uncommitted changes for all the files in this branch using ‘git commit -a -m “<Message>” ’. 

Now push this branch from our local repo to Github using ‘git push origin <branch name>’.



Git clone from GitHub :-
We can clone a forked repo from Github on our local repo. A clone is 
a full copy of a repository, including all logging and versions of files. Move 
back to the original repository, and click the green "Code" button to get 
the URL to clone. Copy the URL.

$ git clone <copied URL>


To specify a specific folder to clone to, add the name of the folder 
after the repository URL, like this -
$ git clone <copied URL> <folder name>









