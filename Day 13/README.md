# Day 13

Today we will learn to update files that already exist in the index.

## Problem Statement:
When we change files, the index won't change on its own. We have to use `git add` to update the index to the changed version of the file.

Let's try that!

The icons in the file browser show you when the actual file (white) and the version in the index (blue) are different, and when they are the same!

### Files:
 - candle

### Questions:
 - Make a change to the candle.
 - Add the candle.
 - Make a commit.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/027d2b5d-aead-4c37-9c75-697021ce5d28" width=400>
  <p>Diagram of the problem</p>
</div>

## Solution:

1. Make a change in the file and save it.
```bash
nvim candle
```

2. Add the file.
```bash
git add candle
```

3. Make a commit and push it.
```bash
git commit -m "candle updated"
git push
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/4ec15c3d-e319-4749-b40d-6f7cfe9a0616" width=450>
  <p>Diagram of the solution</p>
</div>
