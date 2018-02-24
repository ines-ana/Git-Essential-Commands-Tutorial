# Backing out changes

ls —&gt; cd level1 —&gt; ls —&gt; mate level1file.txt

edit file: add some text “isto é para apagar depois!” —&gt; save and close

git status —&gt; git add level1file.txt

we don’t want this changes! —&gt; git status —&gt; git reset HEAD level1file.txt —&gt; git status —&gt; open file to check: mate level1file.txt

revert the changes made to the file:  git checkout -- level1file.txt

git status —&gt; mate level1file.txt —&gt; back to what we had before changing the file!



