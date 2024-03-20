# Day 2

Today we will learn to change the branch of any repository.

Steps:
 - Create a new file `day2.txt` (say).
 - Make a new branch.
 - Make a commit.

Follow the steps to create a new branch and make a commit:

1. Make a new branch.
```bash
git branch master
```

2. Switch to the new branch.
```bash
git checkout master
```
This commands switches the current branch to the new one.

3. Make the commit in the new branch.
```bash
git add day2.txt
git commit -m "file added in new branch"
git push -u origin master
```
