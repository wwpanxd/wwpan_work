Git is distributed version control system.
Git is a free software.

git init
git add readme.txt
git status
git diff readme.txt
git commit -m "worte a message"
git log
git log --pretty=oneline
git reset --hard HEAD^
git reset --hard HEAD~100
git reset --hard commit_id
git reflog # view all histroy version
git checkout -- readme.txt # drop directory changes
rm test.txt
git rm test.txt  # delete file  add to stage
git commit -m "delete test.txt"  # commit remove action to repository
ssh-keygen -t rsa -C "wwpan.xd@163.com"
git remote add origin https://github.com/wwpanxd/wwpan_work.git
git push -u origin master
git push origin master # update to the remote repository
git clone git@github.com:wwpanxd/hello-world.git # clone to local repository form remote repository
git branch
git branch dev
git checkout dev
git checkout -b dev2
git branch -d dev
git checkout master
git merge --no-ff -m " merge" dev
git stash  # save working directory to stash
git merge -m " merged bug fix" issue
git stash list
git stash pop  # get working directory from stash
git stash apply
git stash drop
git stash apply stash@{num}
git pull
git tag v1.0
git tag v1.0  commit_id
git show v1.0
git tag -a v1.0 -m "version 1.0 released" commit_id
git tag -d v1.0
git push origin v1.0
git push origin --tags
git push origin:refs/tags/v1.0



