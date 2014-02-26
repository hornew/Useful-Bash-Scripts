up changes N directories up the directory tree for N passed as an argument.  

For example:

If PWD = /home/austin/scripts/really/deeply/nested/directory/
Then

up 4

would move up the tree 4 directories, changing PWD to /home/austin/scripts
essentially performing cd ../../../..