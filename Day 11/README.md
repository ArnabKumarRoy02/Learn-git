# Day 11

Today we will learn to make commits with more precision (what actually happens in each step).

## Problem Statement:
Welcome to today's lesson! We're going to learn how to make commits with more precision!

Have a look at these two timelines. They have exactly the same outcome. But one of them makes it much easier to figure out what happened.

### Files:
 - ball
 - book
 - candle
 - smoke_detector

### Question:
 - Pick the timeline that's clearer, and make the alarm go off!

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/3e1e22ca-cfad-4fcd-8921-d4e4450c591a" width=450>
  <p>Diagram of the problem</p>
</div>

## Solution:

1. Check out the two branches and the files in them.
```bash
# For all-at-once
git checkout all-at-once
nvim ball book candle smoke_detector

# For step-by-step
git checkout step-by-step
nvim ball book candle smoke_detector
```

2. Determine which branch to choose from.
```bash
git checkout all-at-once
# This branch has a single commit for file changes

git checkout step-by-step
# This branch has 3 different commit for specifying the file changes.
```

3. Make the file changes and make a commit.
```bash
# Make the smoke detector go off
nvim smoke_detector

git add .
git commit -m "smoke detector goes off"
git push
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/bb4de5a7-714b-488e-beae-6ec7d9c4d033" width=450>
  <p>Diagram of the solution</p>
</div>
