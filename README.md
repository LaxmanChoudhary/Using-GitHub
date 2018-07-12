# Using-GitHub
## Basic command lines to learn GitHub on Windows

# SETUP

```
$ get config --global user.email "[valid email]"
set an email address to use as identity for git
```

# INITIALIZATION
```
$ git init
initialize your current directory on the device as a repository on git
```
```
$ git clone [url]
retrieve a entire repository from url at current directory on your device
```

# GitHub stages
```
$ git status
show modified files on your device directory, that are added but not pushed to repo
```
```
$ git commit -m “[descriptive message]”
commit your staged content as a new commit snapshot
```

# Directory Updates from Repo
### Step 1: Move to project directory
```
$ cd "[file_name]"
```
### Step 2: Initiate pull request to up directory with new changes
```
$ git pull origin master
```

# Working with branch
```
create a new branch named "feature_x" and switch to it using
$ git checkout -b feature_x
```
```
switch back to master
$ git checkout master
```
```
and delete the branch again
$ git branch -d feature_x
```
#### a branch is not available to others unless you push the branch to your remote repository
git push origin <branch>
## Note : ``` The $ sign represents the use of terminal commands ```
