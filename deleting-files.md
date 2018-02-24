# Deleting files

Before having the file on git staging area

On terminal —&gt; go to the starter-web folder

create a file: mate doomed.txt, save and close —&gt; got status —&gt; rm doomed.txt \(to delete the file\) —&gt; ls —&gt; git status

File that has been tracked by git

check files tracked: git ls-files —&gt; git rm robots.txt —&gt; git ls-files / ls -&gt; git status -&gt; git commit -m “Deleting new file” —&gt; git status

Backout a staged deletion

git ls-files -&gt; git rm lero-lero.txt -&gt; ls -&gt; git status -&gt; git reset HEAD lero-lero.txt \(unstage the deletion\) -&gt; ls \(lero-lero.txt is not there\) -&gt; git status \(only untamed the deletion but has not restored the file back to the file system\) -&gt; git checkout — lero-lero.txt -&gt; ls -&gt; git status

Delete a file without git \(comand line or file manager - Finder\)

rm lero-lero.txt -&gt; git status \(changes not added to the staging area\) -&gt; git add -A \(add all changes\) -&gt; git status -&gt; git commit -m "deleted lero-lero.txt file” -&gt; git status

Remove outside git an entire nested folder structure

ls -&gt; rm -rf level1/ \(-rf: r = recursive walk the folder struckture, f =n force the deletion\) -&gt; git status -&gt; ls -&gt; git add -A \(add all\) -&gt; git status -&gt; git commit -m "deleting level1 and all children” -&gt; git status

