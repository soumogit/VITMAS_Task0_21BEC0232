
# Basic Git Commands

Hello Everyone!👋🏻 I am Soumodip Ghosh (21BEC0232) from ECE in VIT.


## Commands with Explanation:

## 1. git help

* `git help`

  See all available option for the specific Command

## 2. git config:
                     
```bash
  git config -global user name "[name]"

  git config -global user email [email]
```
This command sets the author name and email address respectively to be used with your commits.


## 3. git commit 

* ```git commit -m "[Type to show any commit massage]```

This command record or snapchat of the file
* ```git commit -a```

This command commits all files you have added or changed with Git.

## 4. git branch:

THis command lists all the branches available in the local repository

* ```git branch [branch_name]```

This command creates a new branch. 


* ```git branch -d [branch_name] ```

THis command delets a branch.


## 5. git status

* ```git status```

This command display the state of workubg directory and stagging area.

## 6. git checkout

* ```git checkout [branch_name]```

This command helps to swap between different repository branches/files/commits

* ```git checkout -b [branch_name]```

This command creates a new branch and switch to the created new branch.

## 7. git push:
* ```git push -u origin master```

This command sends the changes made on the master branch, to remote repository.

## 8. git pull 
* ```git pull```

This command pull everything from the reote server onto local repository.

## 9. git merge
* ```git merge [branch_name]```

This command is used to merge the specified branc's history into the current branch.

## 10. git remote
* ```git remote add origin [remote server link]```


This command is used to connect local repository to the remote server.

## 11. clear
* ```clear```

This command is used to clear the git bash window and bring the command line on top of the computer terminal.


## Start a working Area

| Git Command            | Explaination                                                                |
| ----------------- | ------------------------------------------------------------------ |
| git clone [URL] | Clone a repository in a  |
| git init [repository name] |Create an empty Git respextory or reinitialize an existing one |


## For Changing in File:
| Git Command            | Explaination                                     |
| ----------------- | ------------------------------------------------------------------ |
| git add [file] | Add file contents to the index  |
| git mv | Move or rename a file directory |
| git restore | Restore the non-commited changes |
| git rm | Remove files from the working tree and from the index |

## Examine history and state:
| Git Command            | Explaination                                                                |
| ----------------- | ------------------------------------------------------------------ |
| git bisect | Use binary search to find the commit that introduced a bug |
| git log | Check the commit history in a git repository |
| git status | This command lists all the files that have to be committed. |
| git diff | to look at current changes in your working copy, past changes in commits, or even to compare branches |


