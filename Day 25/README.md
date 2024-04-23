# Day 25

Today we will learn to bisect a commit graph and select both good as well as bad ones.

## Problem Statement:

Oh no! You have lost your key at some point during the day!

Sure, you could look at every single commit in an attempt to find it
but there's a better way: your time machine has a built-in way to find the point in time where things went wrong quickly!

First, play the `bisect start` card. Then, go to a commit where you don't have the key, and play the `bisect bad` card. Likewise, go to a commit early on where you have the key *in your pocket*, and play the `bisect good` card.

After you've found the last good commit, reset the main branch to
it What happened to the key after you lost it?


### Files:
 - you


### Question:
 - Find the last good commit

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/9ce8fe3f-cacb-4608-b571-940cc18c21e2" width=450>
  <p>Description of the problem.</p>
</div>


## Solution:

1. Start the bisect process.
```bash
git bisect start
```

2. Checkout the file on where you find the key, if you don't find it mark it bad.
```bash
git checkout "SHA Code"

# If found key
git bisect good

# Else
git bisect bad
```

3. After founding out where the key is, go to the main file.
```bash
git checkout main
```

4. Reset the commits till the commit where you found the key
```bash
git reset --hard "SHA Code of where you found the key"
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/320807be-594d-4261-9c61-f462dba9edb2" width=450>
  <p>Description of the solution.</p>
</div>
