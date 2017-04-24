Clone existing Remote to Local
--
```
git clone https://github.com/dbl4k/basic-git-commands.git
```
Initialize git local repo
--
```
git init
```
Stage All (-A), ready for Local Commit
--
```
git add -A
```
Stage Current Dir (.), ready for Local Commit
---
```
git add .
```
Commit to Local Repo, with Comment
--
```
git commit -m "first commit"
```
Add Remote Origin Repo (applicable if you used Iinit rather than Clone)
--
```
git remote add origin https://github.com/dbl4k/basic-git-commands.git
```
Change Remote Origin Repo
--
```
git push -u origin master
```
Simply push all Local Commits to Remote
---
```
git push
```
Get Help with Git Push (opens in browser)
--
```
git push --help
```
Create Branch
---
```
git branch secondary
```
Create and Switch To Branch
---
```
git checkout -b secondary
```
Switch to Existing Branch
---
```
git checkout secondary
```
Check The Current Working Branch
---
```
git branch
```
Delete Branch
---
```
git branch -D list
```