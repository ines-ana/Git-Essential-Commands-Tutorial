# Basic Git Workflow \(add, commit, pull & push\)

Inside the project created \(starter-web\)

add a new file: mate lero-lero.txt \(name of file to create\)

git status

add file to the staging area: git add lero-lero.txt

git status

commit file: git commit -m “My first commit!”

git status \(now the file is in the local repository\)

 git pull origin master \(do a pull before doing a push, in case other people are working on the project\) -&gt; git push origin master \(git push will push any commits from the local repository to the remote repository by reference name as well as the branch that you want to push; origin: name of the remote repository we pulled from; master is the name of the branch is the only branch we have right now on the project\)



