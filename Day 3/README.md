# Day 3

Today we will learn to pull aka restore.

Steps:
 - Pull the repository to the targeted location.
 - Make the necessay changes.
 - Push the new changes.

Follow the steps for git pull:

1. Pull the repository at the exact location (SHA code).
```bash
git pull 3aed729477b33b587d09d64a67552cf9a62dba4c
# 3aed729477b33b587d09d64a67552cf9a62dba4c is the unique SHA code for a commit in this repository.
```

2. Edit the file to make the changes.
```bash
nvim day3.txt
# File changes
```

3. Commit the changes.
```bash
git add day3.txt
git commit -m "updated file after git pull
git push -u origin main
```
