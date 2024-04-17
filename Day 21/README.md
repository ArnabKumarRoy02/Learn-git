# Day 21

Today we will learn to undo a bad commit.

## Problem Statement:
Oh no, we made a bad commit! How can we undo making the commit, and go back to a point where we can try again?

The answer is using `git reset [commit]`, which does two things:
 - It resets the current branch ref to the commit you specify.
 - And it resets the index to that commit.

It does not change your working directory in any way, which means that after that, you can try making the commit you want again.


### Question:
 - In the last main commit, the numbers file contains the numbers from 1 to 10.
 - The commit message of that commit is "More numbers".
 - The commit with the typo is not part of the main branch anymore.


### Files:
 - numbers

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/823396f7-af75-4433-8fc4-a45b9575e31e" width=400>
  <p>Description of the problem</p>
</div>


## Solution:

1. Reset the file till that commit.
```bash
git reset "SHA Code"
```

2. Edit the file and make a commit.
```bash
nvim numbers
git add .
git commit -m "More numbers"
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/5c421cdc-d878-4289-bf70-924dfc3d40b2" width=400>
  <p>Description of the solution</p>
</div>
