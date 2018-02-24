# Automatic merges



git checkout -b simple-changes -&gt; mate humans.txt -&gt; do changes -&gt; git commit -am “Adding changes to human.txt” -&gt; git checkout master -&gt; mate README.md -&gt; git status -&gt; git commit -am "Adding copyright value on Readme” -&gt; git log --oneline --graph --decorate --all -&gt; git merge simple-changes -m "Merging changes from simple-changes branch” \(because we know this merge is going to result in a commit\) -&gt; git branch -&gt; git branch -d simple-changes -&gt; git log --oneline --graph --decorate —all \(the branch has no name but it is still intact\)

