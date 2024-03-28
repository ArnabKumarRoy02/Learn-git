# Day 10

Today we will learn to remove contradictions between two merging branches

## Problem Statement:
Sometimes, timelines will contradict each other. <br>
For example, in this case, one of our clients wants these timelines merged, but they ate different things for breakfast in both timelines. <br></br>
Try to merge them together! You'll notice that there will be a conflict! The time machine will leave it up to you how to proceed: you can edit the problematic item, it will show you the conflicting sections. You can keep either of the two versions - or create a combination of them! Remove the `>>>`, `<<`, and `===` markers, and make a new commit to finalize the merge!
Let your finalized timeline be the `main` one.

### Question:
 - Make a breakfast compromise in the `main` branch.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/c8163d84-12e0-4deb-b952-032553985137" width=450>
  <p>Diagram of the problem</p>
</div>

### Solution:

1. Check the contents of the file in all the branches.
```bash
# Check in `muesli` branch
git checkout muesli
nvim sam

# Check in `pancakes` branch
git checkout pancakes
nvim sam
```

2. Try to merge the two branches.
```bash
git merge muesli pancakes
```

3. Fix all the errors and remove the `>>>`, `<<` and `===` and make a commit.
```bash
# Move to the `main` branch
git checkout main
git add .
git commit -m "merged successfully"
git push
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/e9e66ec9-3ce7-472d-b285-af0d36412953" width=450>
  <p>Diagram of the solution</p>
</div>
