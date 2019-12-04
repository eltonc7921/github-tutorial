# git status
**Function:** displays the current state of the directory you are working in and the changes that are on or not on the staging area

*Example 1:*
displays a working directory that has changes
```
~/repository/ $ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        file2.md

no changes added to commit (use "git add" and/or "git commit -a")
```
*Example 2:*
displays a clean working directory
```
~/repository/ $ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
```