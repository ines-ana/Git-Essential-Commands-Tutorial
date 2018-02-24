# Ignoring unwanted files and folders

Git ignore pattern examples

Specific file: MyFile.txt

File pattern: \*.txt

Folder: my-folder/

start by creating an unwanted file: mate access.log \(write there /index.html 200; /something.html 300\) save and close —&gt; git status —&gt; add the gitignore file: mate .gitignore \(write \*.log save and close\) —&gt; ls -al —&gt; git status —&gt; git add .gitignore —&gt; git status —&gt; git commit -m “Adding gitignore file to exclude unwanted files”

we can add folders to gitignore, writing foldername/ in a new line on gitignore \(empty folders are ignored by default as git does not track them\)

