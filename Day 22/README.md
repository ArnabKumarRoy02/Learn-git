# Day 22

Today we will learn to revert changes in a workflow.

## Problem Statement:
We were talking about how to undo a commit, and fix it. 
This only helps when you haven't already pushed it to a remote. 
When that has happened, and you want to undo the effects of the 
commit completely, your best option is `git revert`.

### Questions:
 - The team's main branch no longer contains the bad thing.
 - And the history has not been modified.

### Files:
 - text

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/42f1f785-73f3-4913-9e3e-3fd0b9f8bd0c" width=450>
  <p>Description of the problem.</p>
</div>


## Solution:

1. Create a new commit with the current broken issue.
```bash
git revert "SHA Code"
```

2. Fix the issue.
```bash
nvim text
git add .
```

3. Push the file.
```bash
git commit -m "issue fixed"
git push
```


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/ca0b4b43-0aa4-4bda-8ef3-06fbe5a9c9c1" width=450>
  <p>Description of the solution.</p>
</div>
