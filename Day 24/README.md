# Day 24

Today we will learn to clone a repository and make a PR.

## Problem Statement:
Your friend has a problem! Clone the repo, create a branch called
"solution", and fix the problem in this branch. When you're ready. make a "Pull Request" by using `git tag pr`.

### Question:
 - Complete the goal of this level

### Repository:
 - friend
   - file


<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/052e0ee2-4250-4987-b13f-102e09fecc94" width=450>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Clone the repository.
```bash
git clone ../friend .
```

2. Create a new branch named `solution`.
```bash
git branch -M solution
```

3. Edit the file and make a commit.
```bash
git add .
git commit -m "issue fixed"
```

4. Create a PR into the repository.
```bash
git tag pr
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/4de08d28-41dc-4922-ba97-597a18b127d6" width=450>
  <p>Description of the solution.</p>
</div>
