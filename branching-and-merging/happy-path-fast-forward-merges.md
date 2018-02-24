# Happy path / Fast forward merges

git branch \(list only local branches; -a list both local and remote\) -&gt; git checkout -b title-change \(creates new branch + switches to that new branch\) -&gt; mate simple.html \(change title to “An example website” s&c -&gt; git status -&gt; git commit -am "Changing title of html file” -&gt; git log —oneline — decorate -&gt; git checkout master -&gt; \(is good to review the diffs between master and branch before merging\) git diff master title-change -&gt; git merge title-change \(merge branch with master, merges into current branch\), it was a fast-forward merge so git displaced all commits into master as we didn’t have branched away, we didn’t do any additional work on the master before merging

git log —oneline —decorate -&gt; git branch -&gt; git branch -d title-change -&gt; git branch -&gt; git log —oneline —decorate

