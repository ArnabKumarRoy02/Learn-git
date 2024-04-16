# Day 20

This is a combination of 2 tasks (very simple tasks) so I'm merging them both.

## Problem Statement:
Oops - you deleted the "essay" file, which you worked on all night!

Luckily, Git is here to help! You can use `git checkout` to restore the file!

Here's a similar problem: you really liked the essay from the very first commit, and want to have it back! Well, checkout can also restore things from older commits, Here's how:
```bash
git checkout [commit] [file]
```


### Questions:
 - Restore the essay to contain "important content".
 - Get the first version of your essay, and make a new commit with it.


### Files:
 - essay


Restore Deleted File            |  Restore File from Past
:-------------------------:|:-------------------------:
![](https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/3952294e-57fc-4994-910d-caa01b041f74)  |  ![](https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/3952294e-57fc-4994-910d-caa01b041f74)

<div align="center">
  <p>Description of the problems.</p>
</div>

## Solution:

1. Check out the file.
```bash
git checkout essay
```

2. Checkout the file at the initial commit.
```bash
git checkout "SHA Code" essay
```

3. Make a commit.
```bash
git commit -m "new message"
```

Restore Deleted File            |  Restore File from Past
:-------------------------:|:-------------------------:
![](https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/3952294e-57fc-4994-910d-caa01b041f74)  |  ![](https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/631acb2e-3a7d-476a-8e56-9af3712143da)

<div align="center">
  <p>Description of the solutions.</p>
</div>
