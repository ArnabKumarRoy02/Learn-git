# Day 15

Today we will learn to make changes step by step.

## Problem Statement:
The index is really useful, because it allows us to be precise about which changes we want to include in each commit!

### Files:
 - hammer
 - bottle
 - sugar_cube

### Question:
 - Make changes to all three objects, to form a logical sequence of events!
 - Only add one of these changes!
 - And make a commit.
 - Make a second commit that only records a single change.
 - And a third one.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/6af4d455-181b-4adf-bbc8-4c88cf10012f" width=400>
  <p>Diagram of the problem</p>
</div>

## Solution:

1. Make changes in all the three files and save it.
```bash
nvim hammer bottle sugar_cube
```

2. Add only one file and make a commit.
```bash
git add hammer
git commit -m "hammer added"
```

3. Make a second commit that only records a single change.
```bash
git add bottle
git commit -m "water bottle added"
```

4. Similarly, add the final one.
```bash
git add sugar_cube
git commit -m "sugar cube added"
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/c2b8196b-d461-477a-956a-903abbc1e85a" width=400>
  <p>Diagram of the solution</p>
</div>
