# contains all the commands i used till now

`` git config -h ``
- to get the help for your git config.

`` git init ``
- to this in your local, to initialize your local repo
  - for ex: cd your directory > git init
this will make directory as a git repo

`` git status ``
- will give the current status for the current branch
- will give the commit info,tracked/untracked files


`` git add 'filename'``
- to add/track the 'filename'
(red ones are untracked, green ones are tracked)

``git add .``
- to add all the files

- - - - 
#### .gitignore (git ignore file) *
  - mention all the file names in this file so that the git will not keep track of that files 
    - ex: *.csv or *.txt
- - - - 

- to check if git is ignoring the file or not
  - do ```git status```

- now to create a snapshot of your current version of code
  - do
``` git commit -m "your commit message"```
(this will commit all the files changed/edited/added to the repo)

- to see any differences between files
  -```do git diff```


```git log```
- will show all this commits

```git branch 'newBranchName'```
- will create a new branch named newBranchName

``` git branch```
- to check all the branches in the repo

```git checkout 'branchName'```
- will switch to the branch named branchName

```git branch -d 'branchName'```
- to delete the branch named branchName

- - - - 
#### A basic flow :[To fix something or add a feature, take a pull from the main (get latest), then create a new branch, switch to that branch, make changes, commit, push and then delete the branch] ####

- - - - 
- Clone a remote repo to local and start working on it:
```git clone 'url of the remote git repo'```


```git push```
- to push your changes to the remote branch

#### the other things, like creating pull request,merging can be done in the github or in your editor (vscode) ####




- to push to an existing repository remotely
```git remote add origin 'repolocation ending with.git'```

'add more commands as you explore'
