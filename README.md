# Github Tutorial
###### *by Elton Chan*
---
# Repository Setup
#### Setup using local terminal
1. Create a directory using `mkdir <file>`
2. cd into the directory
3. initialize it using `git init`
4. Create a README.md file using `touch <README.md>`
5. Follow [workflow](#Workflow) commands below
6. Go to [Github](github.com)
7. On the top right of the website, click the `+` and create a new repository
8. Name the repository the exact same name as the one in the local terminal and click `Create repository` without initializing a README.md
9. Select SSH if you have a ssh-key, If not then select HTTP
10. Go back to your ide and use the command `git remote -v` to check if your repository is linked to any remote server. If nothing is there, copy and paste the commands on the github page you were previously on

    *if using SSH:*

    `git remote add origin git@github.com:<username>/<repository name>.git`

    *if using HTTP:*

    `git remote add origin https://github.com/<username>/<repository name>.git`

    *use this after the using the commands previously:*

    `git push -u origin master`

#### Setup using Github
1. On the top right of the website, click the `+` and create a new repository
2. Name the repository and initialize it with a README.md then click `Create repository`
3. Clone the repository by clicking `Clone or download` then copy the HTTP URL or SSH key
4. Go onto your terminal and use [`git clone <HTTP URL or SSH key>`](commands/git-clone.md)

---
### Git Commands
* [git init](commands/git-init.md)
* [git add](commands/git-add.md)
* [git commit](commands/git-commit.md)
* [git push](commands/git-push.md)
* [git pull](commands/git-pull.md)
* [git log](commands/git-log.md)
* [git diff](commands/git-diff.md)
* [git clone](commands/git-clone.md)
* [git revert](commands/git-revert.md)

### Vocabulary
* [Fork](vocabulary/fork.md)
