Branching and Merging

![](/assets/branchesGit.png)![](/assets/featureBranch.png)

### 

# Branching Basics

On terminal and starter-web directory -&gt; git status

Doing all changes in our master is not the best practice. What should be done is separating changes into branches that make the most sense. At least create feature branches or topic branches to isolate changes and then integrate back in the master once these features/topics are stabilised.

git branch -a \(lists both remote and local branches, \* on the current branch\) -&gt; git branch mynewbranch \(create\) -&gt; git branch -a -&gt; git checkout mynewbranch \(swithch branches\) -&gt; git branch -a -&gt; git log —oneline —decorate -&gt; git checkout master -&gt; git branch -m mynewbranch newbranch \(rename by using the move command\) -&gt; git branch -a -&gt; git branch -d newbranch \(delete branch\) -&gt; git branch -a

