# Git-Commands

### Install Git

Open your terminal and run these commands

```bash
  sudo apt update
  sudo apt upgrade
  sudo apt install git
```

### Configure Git

```bash
  git config --global user.name "Your Name"
  git config --global user.email "Your Email"
```

### clone a repository

```bash
  git clone
  cd "repo-name"
```

### Git commands cheat sheet
`git init` : initialize a local git repository.

`git add` : add files to the staging area.

`git commit` : commit changes to head (but not yet to the remote repository).

`git commit -a` : commit any files you’ve changed since then.

`git commit -m "commit message"` : commit with a message.

`git log` : show the commit history for the currently active branch.

`git log --follow [file]` : show the commits that changed file, even across renames.

`git diff` : diff of what is changed but not staged.

`git diff --staged` : diff of what is staged but not yet commited.

`it diff [first branch] [second branch]` : diff of what is in branch A that is not in branch B.

`git show [commit]` : show all the changes made in a commit, even across files and renames.

`git rm [file]` : remove a file from the working tree and from the index.

`git mv [file-original] [file-renamed]` : change an existing file path and stage the move.

`git checkout -- [file]` : discard changes to a file.

`git reset [file]` : unstage a file while retaining the changes in working directory.

`git reset [commit]` : reset your HEAD pointer to a previous commit and discard all changes since then.

`git branch` : list your branches. a * will appear next to the currently active branch.

`git branch [branch-name]` : create a new branch at the current commit.

`git branch -d [branch-name]` : delete the specified branch.

`git push origin [branch-name]` : send the branch to your remote repository.

`git push -u origin [branch]` : push changes to remote repository (and remember the branch).

`git push` : send changes to the master branch of your remote repository.

`git push origin --delete [branch-name]` : delete a branch on your remote repository.

`git pull` : update local repository to the newest commit.

`git clone [url]` : clone a repository that already exists on GitHub, including all of the files, branches, and commits.

`git remote add origin [url]` : add a remote repository that is not on GitHub.

`git remote -v` : show all remote repositories.

`git fetch` : fetch down all the branches from that Git remote.

`git merge [branch]` : merge a different branch into your active branch to bring it up to date.

`git rebase [branch]` : apply any commits of current branch ahead of specified one.

`git show [tag]` : see information about a tag.

`git pull` : fetch and merge any commits from the tracking remote branch.