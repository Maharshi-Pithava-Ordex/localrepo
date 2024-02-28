# Local Repo

it is a local repostory
<br>
new changes in staging area

<!-- basic commands -->

git status
git add .
git commit -m "msg"
git push origin main

<!-- direct commit -->

git commit -a -m "msg"

<!-- check changes -->

git diff
git diff --staged

<!-- git log commands -->

git log --stat
git log -p
git log --pretty
git log --pretty=oneline
git log --pretty=short
git log --pretty=long
git log --since=2.days
git log --pretty=format:"%h - %an"

<!-- rename file -->

git mv index.html home.html

<!-- revert last commit -->

git reset HEAD~1

<!-- branch commands -->

<!-- change master to main -->

git branch -M main

<!-- create new branch  -->

git checkout -b feature1

<!-- delete new branch -->

git branch -d feature1

<!-- change branch -->

git checkout feature1

<!-- merge branch -->

git merge

<!-- unstaged file -->

git restore --staged filename
