# gitess - The Git essentials

```
git config   
```
*This is a command for setting your user name and email in the main configuration file. To check your email or user name, use ```git config --global user.name and git config — global user.email ```. Similarly, you can set your new name or email by using ```git config --global user.name = “Zaur Fataliyev”``` or ```git config --global user.email = "fvzaur@gmail.com"```.*

```
git init
```
*This is a command for initializing a git repository for a new or existing project. In order to initialize a new git repository, use ```git init``` command in the root of your project directory.*

```
git clone
```
*This is a command to copy a git repository from remote source, also sets the remote to original source so that you can pull again. To copy/clone the repository at URL, use ```git clone URL``` command.*

```
git status
```
*This is a command to check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit. To check your repository status, use ```git status``` command in your working directory. It lists out all the files that have been changed.*

```
git add
```
*This is a command for adding changes to stage/index in your working directory. To add all changes in current repository, use ```git add .``` command in working directory.*

```
git commit
```
*This command commits your changes and sets it to new commit object for your remote. To commit your updates, use ```git commit -m "Your commit message"``` command.*

```
git push
```
*This command pushes your changes to remote. If you have added and committed your changes and you want to push them, use ```git push``` command.*

```
git pull
```
*This command pulls changes from a remote repository into the current branch. If your remote has updated and you want those latest changes to current working branch, use ```git pull``` command.*

```
git branch
```
*This command lists out all the branches. To list all branches of current repository, use ```git branch --all``` command.*

```
git checkout
```
*This command is used to switch to different branches. To checkout your desired branch, use ```git checkout <branch>``` command,  or use ```git checkout -b <branch>``` command if you want to create and switch to a new branch.*

```
git stash
```
*This command is for to save changes that you don’t want to commit immediately. To do this, use ```git stash``` command in your working directory. Use ```git stash apply``` command if you want to bring your saved changes back.*

```
git merge
```
*This command is used to merge two branches you were working on. To do this, switch to branch you want to merge everything in and use ```git merge <branch_to_merge>``` command. *

```
git reset
```
*This command is used when you know when you commit changes that are not complete, this sets your index to the latest commit that you want to work on with. To do this, use ```git reset <mode> <commit>``` command.*

```
git remote
```
*This command is for checking what remote/source you have or add a new remote. To do this, use ```git remote``` command to check and list. Moreover, ```git remote add <remote_name> <remote_url>``` command to add the new remote.*
