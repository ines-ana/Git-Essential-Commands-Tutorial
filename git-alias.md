# Git Alias

in starter-web project:

git status —&gt; create extra commands that work along side with git:

git log — all —graph —decorate —oneline is a git command, but we want to create a new command do execute de same faster, lets call it git hist

git hist —&gt; not known —&gt; git config --global alias.hist "log --all --graph --decorate —oneline" —&gt; git hist —&gt; git config —list \(alias is defined there!\)

