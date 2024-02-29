# Local Repo

it is a local repostory
<br>
new changes in staging area

<!-- basic commands -->

git status <br>
git add . <br>
git commit -m "msg" <br>
git push origin main

<!-- direct commit -->

git commit -a -m "msg"

<!-- check changes -->

git diff <br>
git diff --staged

<!-- git log commands -->

git log --stat <br>
git log -p <br>
git log --pretty <br>
git log --pretty=oneline <br>
git log --pretty=short <br>
git log --pretty=long <br>
git log --since=2.days <br>
git log --pretty=format:"%h - %an"

<!-- rename file -->

git mv index.html home.html

<!-- revert last commit -->

git reset HEAD~1

<!-- branch commands -->

git branch

<!-- change master to main -->

git branch -M main

<!-- create new branch  -->

git checkout -b feature1

<!-- delete new branch -->

git branch -d feature1

<!-- show branches with last commit -->

git branch -v

<!-- change branch -->

git checkout feature1

<!-- merge branch -->

git merge

<!-- unstaged last stage -->

git restore --staged filename

<!-- return last commit changes of file -->

git checkout -- filename

<!-- remote github repository -->

git remote add origin link <br>
git remote <br>
git remote -v

<!-- add alias for minified commands  here st replace status-->

git config --global alias.st status

<!-- remove git tracking -->

git rm -r --cached

<!-- remove .git folder -->

Remove-Item ".git" -Force -Recurse
