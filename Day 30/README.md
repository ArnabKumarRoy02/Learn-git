# Day 30

Today we will learn to merged popped stash.

## Problem Statement:

When you want to reapply your changes but you already continued working on your file, you might get a merge conflict! Let's practise this situation.

Pop the changes from the stash with `git stash pop` and resolve the merge conflict. Commit the resolved changes and clear the stash stack afterwards.

### Files:
 - recipe

### Questions:
 - Did you resolve the confict and commit?
 - Did you clear stash stack?


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/2f7b1795-c0d9-431d-9da6-62777d07e4cf" width=450>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Check out the stash list.
```bash
git stash list
```

2. Pop the stash item.
```bash
git stash pop
```

3. Edit the files necessary to commit.
```bash
# Edit files
nvim recipe

# Add the file and commit it
git add .
git commit -m "updated"
```

4. Clear out the stash list.
```bash
git stash clear
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/8b78fce3-9101-45f6-aeb7-d63760fe89d0" width=450>
  <p>Description of the solution.</p>
</div>
