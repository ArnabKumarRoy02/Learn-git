# Day 7

Today we will learn to delete branches.

Problem Statement:

Life is full of dangers, right? Even when walking to school, it seems like there's a lot of risks!
This Monday is especially bad. You made it to school, but there's some timelines you definitely don't want to keep around.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/84052298-d5ec-4076-b425-1f98acad0956" width=450>
  <p>Figure: Diagram describing the problem</p>
</div>

Question:
 - Find the bad branches and delete them. Keep only the best one.

Solution:

1. Checkout the content of the file in each branch.
```bash
git checkout friend
git checkout music
git checkout leap
git checkout ice-cream
```

2. You find that the `leap` branch was the best.
```bash
git reset --hard
```

3. Delete the unnecessay branch and keep the one only needed.
```bash
git branch -D friend music ice-cream
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/19cb29a0-e6ee-4460-97d2-f83972b3ab1c" width=450>
  <p>Figure: Diagram of the solution</p>
</div>
