# Day 17

Today we will learn to sync files that 2 or more people are working on simultaneously.

## Problem Statement:
Both you and your friend have been working on the file, and want to sync up!

### Question:
 - Commit your local changes.
 - Look at your friend's suggestion, make a compromise, and push it back.

### Files:
 - file


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/4023a22b-8d4b-4627-94c0-3d44a68d2b4e" width=450>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Add the file from your side.
```bash
git add .
git commit -m "file updated"
```

2. Pull the request the friend made.
```bash
git pull
```

3. Edit the file and make the necessay changes.
```bash
nvim file
git add .
git commit -m "file commited with sync"
```

4. Push the file to update on both side.
```bash
git push
```


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/57159d78-58ca-4d79-9756-0a328843f950" width=450>
  <p>Description of the solution.</p>
</div>
