# Day 4

Today we will learn how to make parallel commits.

Steps:
 - Checkout the changes in file over all the commits.
 - Update the files, however necessay.
 - Commit the files.

To make parallel commits, take the necessay steps:

1. Checkout where do we need to make some changes.
```bash
git checkout "SHA code"
```

2. Update files
```bash
nvim file.txt
# Make the changes.
```

3. Commit the files.
```bash
git add file.txt
git commit -m "made a parallel commit"
git push -u origin main
```
