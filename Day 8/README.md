# Day 8

Today we will learn to move around different branches.

## Problem Statement:
One of your colleagues messed up here, and put the branches in the wrong timelines!<br>
You could delete and re-create these branches - but you can also directly move them to different commits, by using:
```bash
git checkout
```

on the branch names, and then using:
```bash
git reset --hard
```

on the commit where you want the branch to be.

The donut branch is in the right place, but the timeline is still incomplete - make you actually *eat* the donut in that branch!

### Questions:
 - Did you eat a baguette on the baguette branch?
 - Did you drink a coffee on the coffee branch?
 - Did you eat a donut on the donut branch?

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/4fe7bebc-76b4-4776-b159-7537c34eb4e1" width=450>
  <p>Diagram of the problem</p>
</div>

## Solution

1. Checkout all the different branches and the file.
```bash
git checkout baguette
git checkout coffee
git checkout donut

# Check the file
nvim you.txt
```

2. After checking the file, reset or delete the branch.
```bash
git branch -D baguette
git branch -D coffee
```

3. Then go the respective position on where the actual branch should be there.
```bash
git checkout SHA Code

# Then create the branch that is required.
git branch baguette

# Again for branch - coffee
git checkout SHA Code
git branch coffee
```

4. Go to the donut branch and make the changes.
```bash
git checkout donut

# Make the changes and commit
git add .
git commit -m "ate donut"
git push -u origin main
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/52dce6f1-7dfa-4f07-acdf-69296fd3afbb" width=450>
  <p>Diagram of the solution</p>
</div>
