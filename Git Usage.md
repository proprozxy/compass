## Git Usage

**configuration**

```bash
git config --global user.name <username>
git config --global user.email <email>
git config --list
```

**create new branch**

```bash
git clone git@github.com:xxx.git -b base_branch
git checkout -b new_branch
git push -u origin new_branch
```

**check status**

```bash
git status uno
```

use `git status uno` to ignore untracked files

**generally push**

```bash
git add <file>
git commit -m "commit message"
git push
```

can use `git add .` to add all files

**temporary storage**

```bash
git stash
git stash pop
```

**rollback commit**

rollback last commit

```bash
git revert HEAD
git push
```

go back to the specified commit and undo the commits after it

```bash
git log
git reset --hard <commit hash>
git push --force
```

`git reset` has 3 modes

`--soft` roll back to the last commit but keep changes to the working directory  
`--mixed` (default) roll back to the last commit, retaining changes in the working directory, but not in the staging area  
`--hard` completely roll back to the last commit without retaining any changes in the working directory and staging area

**submodule**

first time pull submodule

```bash
git submodule update --init --recursive
```

