# Day 6

Today we will learn how to grow branches with you.

Problem Statement:

Note that there are two options to "travel to the end of a timeline": 

First, you can directly travel to the commit, like we've done it before. 

And second, you can travel to the branch label. In this case, when you make a new commit, the branch will grow with you, and still point at the end of the timeline!

To travel to a branch, type:
```bash
git checkout name_of_the_branch
```
And to travel to the last commit, type:
```bash
git checkout --detach
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/ddf451c1-34db-4bcd-8758-b06d3a776384" width="400">
  <p>Figure: Diagram to explain the state of the problem</p>
</div>

Questions:
<ul>
  <li>Travel directly to the last yellow commit of the birthday timeline, make a change to 'you', and make a commit.</li>
  <li>Travel to the blue 'concert' branch, make a change to you', and a commit.</li>
</ul>


Solution:

1. Go to the last commit in the `birthday` branch.
```bash
git checkout --detach birthday
```

2. Make the necessary file changes and make the commit.
```bash
nvim you.txt
git add .
git commit -m "message"
git push -u origin main
```

3. Now switch to the concert branch.
```bash
git checkout concert
```
4. Make the files changes and commit it.
```bash
nvim you.txt
git add.
git commit -m "new message"
git push -u origin main
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/57a66173-9b34-4496-b8c1-0deaf3524184" width="400">
  <p>Figure: Final diagram of the solution</p>
</div>
