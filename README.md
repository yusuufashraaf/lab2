1- creating new project on the local machine ,the push it to remote repo
-- cd desktop 
-- mkdir lab2 
-- cd lab2
-- touch > README.md
-- git init
-- git add README.md
-- git commit -m "first commit"
-- git branch -M main
-- git remote add origin git@github.com:yusuufashraaf/lab2.git
-- git push -u origin main

2- create two branch 
 -- git checkout -b dev 
 -- git add devfile.txt
 -- git commit -m "adding dev file"
 -- git push -u origin dev
 
  -- git checkout -b test 
 -- git add testfile.txt
 -- git commit -m "adding test file"
 -- git push -u origin test
3 merging them
-- git checkout main
-- git pull origin main
-- git merge dev
-- git add devfile.txt
-- git commit -m "adding devfile.txt"
-- git push origin main

-- git checkout main
-- git pull origin main
-- git merge test
-- git add testfile.txt
-- git commit -m "adding testfile.txt"
-- git push origin main

4- removing locally and remotely
--locally 
git reset --hard HEAD~1

--remotely
git revert with sha1

5- checkout another branch
-- git stash 
-- git checkout -b newBranch
-- git stash apply

6- 
