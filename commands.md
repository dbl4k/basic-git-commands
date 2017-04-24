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
Stage All (-A) Newly Created  Files, ready for Local Commit
--
```
Stage Current (.) Newly Created Directory, ready for Local Commit
```
*or just add currentdirectory*
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