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
