# Day 12

Today we will learn to do the most simple and one of the first commands when we start git.

## Problem Statement:
So far, when we made a commit, we've always recorded the current status of all objects, right?

But Git allows you to pick which changes you want to put in a commit!

To learn how that works, we need to learn about the "index"! In the index, we can prepare what will be in the next commit. In this game, the index is represented by a blue aura around icons in the file browser!

Initially, the index is empty. To make a commit that contains a new file, we need to add it!

### Files:
 - candle

### Question:
 - Add the candle.
 - Make a commit.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/885b11da-2b12-4419-a865-af392e15281f" width=400>
  <p>Diagram of the problem</p>
</div>

## Solution:

1. Add the file `candle`.
```bash
git add candle
```

2. Make a commit.
```bash
git commit -m "candle added"
```

3. Push it.
```bash
git push
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/b59688de-8e72-4985-82b4-e69ed35f169e" width=400>
  <p>Diagram of the solution</p>
</div>
