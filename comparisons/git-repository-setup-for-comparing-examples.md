Git Repository Setup \(for comparing examples\)

can also add here the tools to use



### Visual Merge / Diff Tool installation

download p4merge

p4merge will be stored in the Applications folder, that is inside the root directory \(/ on terminal, called Macintosh HD on my computer\)

to go there from your user directory \(on terminal\) write cd ../.. —&gt; open Applications/p4merge.app \(to open p4merge\) —&gt; cmd + q —&gt; close terminal

We already have a diff tool defined globally in our system, that is source tree. For this course I’m going to set a local diff tool inside one of the dummy github projects

set up p4merge from terminal: open terminal -&gt; /Applications/p4merge.app/Contents/MacOS/p4merge \(check that we can open p4merge\) -&gt; \(go to github folder\) cd Documents/github/github-demo -&gt; \(check .gitconfig file\) mate .gitconfig \(it’s empty\) -&gt; git config --local diff.tool p4merge -&gt; \(define path\) git config --local difftool.p4merge.path “/Applications/p4merge.app/Contents/MacOS/p4merge" -&gt; git config --local difftool.prompt false \(prevent git to ask you if you want to launch p4merge every time you invoke it\) -&gt; git config —local —list -&gt; git config --local merge.tool p4merge \(config p4merge to also be the merge tool\) -&gt; git config --local mergetool.p4merge.path “/Applications/p4merge.app/Contents/MacOS/p4merge" -&gt; git config --local mergetool.prompt false -&gt; mate .git/config \(check changes made\)



### Git repository setup \(for comparison examples\)

go to starter-web project -&gt; ls -&gt; we have a readme file \(README.md\) -&gt; change and add titles \(\#\# Introduction and \#\# How to contribute\) -&gt; git status -&gt; git add README.md -&gt; git commit -m “Changing readme file” -&gt; git push origin master -&gt; check on remote project directory \(GitHub\) -&gt; mate README.md -&gt; add a section called \#\# Deployment, save&close -&gt;  git commit -am "Adding a new section: deployment”\(-am add + message\) -&gt; git push origin master -&gt; now edit the readme file with 1 change and add that change to the starting area and also create another change but do not add it.

This is the base for us to study git comparisons!

