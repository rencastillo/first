ls: list the contents of a directory
ls-l: used to show the size, last modified date-time as well as directory/file ownership and permissions.
ls-a: list all entries including those with .(period) and ..(double period)
open: shows file by writing open “filename” - cd: change to another directory
pwd: print the working directory. Show where I am at the moment
mkdir: create a new directory
mv: to move archive into another
man: gives you a manual entry of what that command does
clear: clears screen
touch: allows you to create any type of file, but it’s blank.
sudo: allows you to elevate your user privileges while executing the command to administrator privileges. This is required for some commands to run —for instance removing a file that is owned by another user. When you run this command, you will see a password field appear in the Terminal where you will need to type your user account password to finish the command execution. sudo "command".
nano: opens the terminal editor
Git commands

git clone: download a repository to the local machine
git status: check the current situation of the local repositary
git add: add files to the staging area before commiting
git commit: register the changes into the history of the repository
git commit--amend: Passing the --amend flag to git commit lets you amend the most recent commit. This is very useful when you forget to stage a file or omit important information from the commit message.
git push: send local changes to github
git branch: this command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.
git checkout: checks out old commits and old file revisions, it is also the means to navigate existing branches. Combined with the basic Git commands, it’s a way to work on a particular line of development.
git clean: removes untracked files from the working directory. This is the logical counterpart to git reset, which (typically) only operates on tracked files.
git fetch: fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.
git log: lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.
git pull: pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.
