# git_example
How to upload code to github
Resource:
https://blog.techbridge.cc/2018/01/17/learning-programming-and-coding-with-python-git-and-github-tutorial/

git --version
git config --global user.name "your name"
git config --global user.email “e-mail address”

cd hello-git
git init
ls -la

git status

git add hello.py
git status
git commit -m "Init hello.py"
git status

git remote add origin <https://github.com/currysesame/sort_method>

git status
git push -u origin master
