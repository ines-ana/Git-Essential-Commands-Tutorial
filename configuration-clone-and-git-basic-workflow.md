# Configuration, Clone, and Git Basic Workflow

Confirm git is available: in terminal “git version”

configure our account: \(substitute —global for —local\)

git config —global user.name “Ines Ana”

git config —global user.email “ines.santa.ana@gmail.com"

to confirm what has been defined

git config —global —list





Go to GitHub and look for the url of the project \(HTTPS done url\), copy the url

on terminal, inside the folder we want to create the local repository, write:

git clone \(past url without “”\) —&gt; copy of the repository to our local system

command “git status” shows us we’re in the branch master and there’s nothing to commit



**We use the git status command to see if there are any differences between the working directory, the staging area,, our local repository and our remote repository.**

add a file to the local repository

then check status: git status \(will say there are untracked files\)

git add fine\_name\_here \(adds the file to the staging area\)

git status will say there are uncommitted changes

to commit: git commit -m “Write commit message here”

 check git status \(now the file has been committed to the local repository, is not on the remote rep yet; check this on gitHub only\)

push the changes to the remote rep: git push origin master \(have to add our user-name and password\)

check on browser if the file is there

