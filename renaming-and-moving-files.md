# Renaming and moving files

### Renaming:

### 

### Using the command prompt with git commands

cd level1/level2/level3 —&gt; pwd —&gt; ls —&gt; git status

rename the file: git mv level3file.txt level3.txt \(mv is for move, then have the old name and the new b+name, or the old placement and the new placement\) —&gt; ls —&gt; git status —&gt; git commit -m “Renaming the file level3”

output gives a confidence level 100% —&gt; always rename the files before making any changes, this makes it easy for git to track the fact that the rename has happened \(???\)

### 

### Through the operating system \(also through the command line, but without git commands\)

cd .. —&gt; pwd —&gt; ls —&gt; git mv level2file.txt 2.txt —&gt; ls —&gt; git status —&gt; 

move level2 file to level3 folder: git mv level2file.txt level3 —&gt; ls —&gt; cd level3 —&gt; ls —&gt; git status —&gt; git commit -m "moving file from level2 to level3” —&gt; git status

put the file back: mv level2file.txt .. —&gt; ls —&gt; cd .. —&gt; ls —&gt; git status \(git says we have deleted a file and created a new one, because the move was done without the git command\) —&gt; git add -A —&gt; git status —&gt; git commit -m “moving file back to level 2” —&gt; git status

### 

### 

### Through Finder \(outside of command line\)

rename file level1file.txt to level1.txt —&gt; git status —&gt; git add level1.txt —&gt; git status —&gt; git add -u \(for git to understand we have renamed the file\) —&gt; git status —&gt; git commit -m “rename level 1 file” —&gt; git status

