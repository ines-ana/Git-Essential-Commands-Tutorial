# Recursive Add

How to recursively add files to the git repository

from the starter-web project, create a deep nesting folder structure: mkdir -p level1/level2/level3

add files to each nested folder created:

\(use lero-lero\)

cd ../../.. —&gt; ls —&gt; git status \(only shows level1 not added because they are not being tracked yet, to add all new files do “git add . “ \) —&gt; git status

git commit -m "Adding several files recursively”



![](/assets/RecursiveAdding_example.png)

