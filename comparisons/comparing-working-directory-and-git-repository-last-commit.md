# Comparing working directory and the GIT Repository \(last Commit\)

git status -&gt; git diff HEAD \(compares WD and the last commit on this branch\) -&gt; git difftool HEAD

ls -&gt; mate simple.html \(write Simple title as the title\) -&gt; git status -&gt; git diff -&gt; git diff -- README.md \(returns only the change on that specific file\), same as git difftool -- README.md

![](/assets/Comparing_example.png)

