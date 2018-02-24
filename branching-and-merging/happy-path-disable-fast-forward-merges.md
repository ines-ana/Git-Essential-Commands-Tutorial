# Happy path / disable forward merges

git checkout -b add-copyright -&gt; git branch -&gt; mate simple.html \(add copyright comment\) -&gt; git status -&gt; git commit -am “Adding copyright notice” -&gt;  mate README.md \(add copyright section\) -&gt; git commit -am “Adding copyright notice to Readme file”



![](/assets/Merge_no_fast_forward.png)



git log —oneline —graph —decorate -&gt; git checkout master -&gt; git merge add-copyright —no-ff \(merge commit\) -&gt; git log —oneline —graph —decorate \(the graph line has been preserved, we still see the branch\) -&gt; git branch -d add-copyright \(deleting\)

