# Day 29

Today we will learn to keep the changes in stash within another branch.

## Problem Statement:

If you want to keep your changes but they don't belong to the main branch, you can easily
create a new branch from your stashed changes. Just use: <br>
`git stash branch ‹branchname> ‹stash>`

If you just want to use the latest stash entry, you can leave the «stash> option empty. <br>
Create a new branch from the stashed changes!

### Files:
 - recipe


### Question:
 - Did you create a new branch from the stashed changes?

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/ac4c253e-5792-4474-9f4d-2c6c1065fe26" width=450>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Checkout the stash list to check which stash to remove.
```bash
git stash list
```

2. Create a new branch in particular stash.
```bash
git stash branch new stash@{0}
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/303244a3-a7ba-4088-811e-3b4b8b6c3a43" width=450>
  <p>Description of the solution.</p>
</div>
