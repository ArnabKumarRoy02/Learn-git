# Day 32

Today we will learn to delete tags.

## Problem Statement:

You added way too many tags? No prob! Delete them with <br>
`git tag -d ‹tag-name>`

Remove all tags in this repo!

### Files:
 - feature-list


### Questions:
 - Did you remove all tags?

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/ff6a7b98-f585-4061-916b-1959d1cc5b82" width=400>
  <p>Description of the problem.</p>
</div>

## Solution:

1. Delete all the tags one-by-one.
```bash
git tag -d v1
git tag -d v2
git tag -d v3
```

or

2. Delete all the tags at once.
```bash
git tag -d v1 v2 v3
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/b5b832a6-d019-4a8c-bd77-4a6d956b33db" width=400>
  <p>Description of the solution.</p>
</div>
