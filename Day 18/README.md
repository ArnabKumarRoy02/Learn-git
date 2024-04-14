# Day 18

Today we will learn how to rebase different branches of workspace.

## Problem Statement:
Okay - turns out that saving time in the morning by utilizing parallel universes is against the regulations of the International Time Travel Association. You'll have to do your tasks in sequence after all.

See the `rebase` card? When you drag it to a commit, it will copy the events in your current timeline after the specified one! This way, make a clean, linear timeline where you visit all three shops.

Again, we want to make that our base reality - the `main` branch should point to that timeline!

### Question:
 - Order all tree branches into one and move the main branch ref.

### Files:
 - you

<div align="center">
    <img src="image.png" width=450>
    <p>Description of the problem.</p>
</div>


## Solution:

1. Rebase the first branch (here it's baguette).
```bash
git rebase baguette
```

2. Checkout the `main` branch and rebase it again.
```bash
git checkout main
git rebase baguette
```

3. Repeat the process for `donut` and `coffee` as well.
```bash
git rebase coffee
git rebase donut
```

<div align="center">
    <img src="image-2.png" width=450>
    <p>Description of the solution.</p>
</div>