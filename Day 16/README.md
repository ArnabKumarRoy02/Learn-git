# Day 16

Today we will learn to manage conflicts between two different commits from different sources.

## Problem Statement:
Your friend added another line to your essay! Get it, add a third one and send it to them!

Take turns until you have five lines!

### Files:
 - essay

### Questions:
 - Got the second line from your friend
 - Got the fourth line from your friend.
 - The friend got a third line from you
 - The friend got a fifth line from you

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/6be8b3c8-5047-4ec4-a059-1853fbbd566b" width=600>
  <p>Description of the problem</p>
</div>

## Solution:

1. Pull all the content of the file.
```bash
git pull
```

2. Add a 3rd line as per the requirement.
```bash
nvim essay
git add essay
git commit -m "Line 3 added"
```

3. Pull all the content again for the 4th line.
```bash
git pull
```

4. Add the 5th line as per requirement.
```bash
nvim essay
git add essay
git commit -m "Line 5 added"
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/edf29365-37cf-4224-8e16-f35c54f63859" width=600>
  <p>Description of the solution</p>
</div>
