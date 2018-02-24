# Comparing Between commits 

git log —oneline -&gt; git diff 60d0c44 HEAD shows differences between the specific commit and the act commit \(HEAD\)

git diff HEAD HEAD^\(compares head and head -1\), same as git difftool HEAD HEAD^

diff between 2 specify commits: git diff 4107071 fb17340, same as git difftool 4107071 fb17340 \(cmd + q to quit, p4merge shows one file at a time\)

