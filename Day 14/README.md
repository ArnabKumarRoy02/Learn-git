# Day 14

Today we will learn to reset files in the index.

## Problem Statement:
See the dark shadow behind the icons? That's the version of the file in the last commit!

For example, these candles have been blown out, and that change has been added.

But you decide that this was a mistake! You only want to blow out the red candle in the next commit!
If you already have updated the index to a changed file, but want to reset it, you can use `git reset`!

### Files:
 - blue_candle
 - green_candle
 - red_candle

### Questions:
 - Reset the changes in the green and blue candles!
 - And make a commit!

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/1c76c9af-76ea-46a1-a113-6568fdac1ccb" width=400>
  <p>Diagram to the problem</p>
</div>

## Solution:

1. Reset the files needed for change.
```bash
git reset blue_candle green_candle
```

2. Make a commit.
```bash
git commit -m "green and blue"
git push
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/94d30381-522e-48d1-8a8b-d93ae8050269" width=400>
  <p>Diagram to the solution</p>
</div>
