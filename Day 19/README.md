# Day 19

Today we will learn on how to cherry-pick commits in a repository in order to make a correct sequence.

## Problem Statement:
Oops, looks like there's something messed up here. Can you put the events back into their correct order?

There are two ways to do this: You can drag the "interactive rebase" card to the commit before the one you want to change, then reorder the lines in the file that opens, and save it.

Or you can reset the main tag to the very first commit, and then cherry-pick single commits in the order you want. You have cards for both approaches!

### Question:
 - Reorder the commits to dress yourself in the correct way

### Files:
 - you


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/b9d99ed9-5431-4cf6-b097-be24f4c4d9ff" width=450>
  <p>Description of the problem</p>
</div>

## Solution:

1. Go to the start of the commits.
```bash
git checkout "SHA Code of begining"
```

2. Start cherry-picking the correct way.
```bash
git cherry-pick "SHA Code of choice"
# Continue till you complete all the commits
```

3. Hard Reset the main to the new commits.
```bash
git checkout main
git reset --hard "SHA code of final"
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/190047cd-8fc7-482a-8ce1-ea8dd763a9bb" width=450>
  <p>Description of the solution</p>
</div>
