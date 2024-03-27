# Day 9

Today we will learn how to merge branches

## Problem Statement

Here's a trick so that you can sleep a bit longer: just do all your morning activities in parallel universes, and then at the end, merge them together!

### Questions:
 - Build a situation where you consumed a baguette, a coffee, and a donut.
 - Be on a merge commit.

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/47f005b9-c801-4ca5-aae7-ae012e4e13b4" width=450>
  <p>Diagram of the problem.</p>
</div>

## Solution

1. First checkout the content of the file in each commit.
```bash
git checkout SHA Code
```

2. Create new branches where updates were made.
```bash
# Ate a baguette
git branch baguette

# Drank Coffee
git branch coffee

# Ate a donut
git branch donut
```

3. Merge all the different branches, this creates a new commit altogether.
```bash
git merge baguette coffee donut
```

<div align="center">
  <img src="https://github.com/ArnabKumarRoy02/Learn-git/assets/86621483/25106b02-114a-4a14-a86f-4026e1877272" width=450>
  <p>Diagram of the solution.</p>
</div>
