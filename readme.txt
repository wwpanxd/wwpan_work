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
