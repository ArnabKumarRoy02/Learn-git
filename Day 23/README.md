# Day 23

Today we will learn to go back on where we were before.

## Problem Statement:
Say you were looking at something in the past, and then switched back to the main branch.

But then, you got really distracted, and after your lunch break, you can't remember on which commit in the past you were before. How can you find out?

There's a convenient command that shows you all the places your
HEAD did point to in the past:
`git reflog`

### Question:
 - Find out where you've been before, and go back there!


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/113f1a05-4cca-46e3-a4eb-00d49cd3eb0b" width=750>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Use the reflog command to find out the pattern.
```bash
git reflog
```
The output of the above command comes out to.
```term
726971f (HEAD -> main, 10) HEAD@{0}: checkout: moving from 3 to main
151f810 (3) HEAD@{1}: checkout: moving from main to 3
726971f (HEAD -> main, 10) HEAD@{2}: commit: 10
06a8ddd (9) HEAD@{3}: commit: 9
4a9b680 (8) HEAD@{4}: commit: 8
0236645 (7) HEAD@{5}: commit: 7
b5a3437 (6) HEAD@{6}: commit: 6
7df3b91 (5) HEAD@{7}: commit: 5
1113cb6 (4) HEAD@{8}: commit: 4
151f810 (3) HEAD@{9}: commit: 3
97c719a (2) HEAD@{10}: commit: 2
374d0a3 (1) HEAD@{11}: commit (initial): 1
```

2. From the output, you found that we need to go to the 3rd branch.
```bash
git checkout 3
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/3186f0cb-261f-4b8d-b5bf-fc3f0e2d510e" width=750>
  <p>Description of the solution.</p>
</div>
