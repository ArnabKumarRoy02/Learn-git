# Day 34

Today we will learn to make remote tags.

## Problem Statement:

When you work with remote repositories, tags are not pushed or pulled automatically.

You can push a tag with:<br>
`git push <remote> <tag-name>`

Or all tags with:<br>
`git push ‹remote> --tags`

Deleting tags on your remote works with: <br>
`git push ‹remote> --delete <tag-name>`

You can also sync: <br>
`git fetch <remote> --prune --prune-tags`

Add a tag named "v2" to the last commit and push it to the remote.
Also pull the vl tag to your local repository.

### Files:
 - project-ideas

### Questions: 
 - vi tag in your repo
 - v2 tag in your repo
 - v2 tag in the remote

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/f49ee33d-8a78-4637-8a47-41563bda5579" width=400>
  <p>Description of the problem.</p>
</div>


## Solution:

1. Pull the recorded updates.
```bash
git pull
```

2. Add the v2 tag in the local repository.
```bash
git tag v2 "SHA Code"
```

3. Push the tag so that the friend also get it.
```bash
git push friend v2
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/343a2843-106f-48f3-be75-d421e5a7f28c" width=400>
  <p>Description of the solution.</p>
</div>
