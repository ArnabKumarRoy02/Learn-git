# Day 5

Today we will learn on Creating Branches.

Problem Statement: 
You were invited to two parties! At one of them, your favorite band is playing - and the other one is your best friend's birthday party.
Where should you go? 

No worries - as a time travel agent in training, you can go to both parties! 

To make it easier to tell which timeline is which, you can create time portals! (We call these "branches".)

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/b62a4fc8-d236-4fa2-afd5-3ec85d005b1e" width="400">
  <p>Figure: Diagram of the problem describing the current state</p>
</div>

Questions:
<ul>
  <li>Create a branch called `birthday` that points to the birthday timeline.</li>
  <li>Create a branch called `concert` that points to the birthday timeline.</li>
</ul>

To solve this problem: 
1. Go to the commit you want first (say birthday).
```bash
git checkout SHA Code
```

2. Create a new branch name birthday.
```bash
git branch birthday
```
3. Then go to the base commit and repeat the same steps for concert.
```bash
git checkout SHA Code
git branch concert
```
