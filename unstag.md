# Unstaging on git stage

Unstaging on or in Git stage refers to the process of removing files or changes from the staging area, also known as the index, before they are committed to the repository.
 This action effectively undoes a git add operation, returning the files to a "modified but not staged" state in the working directory. 
The changes themselves are preserved in the working directory and are not lost.

``` git restore --staged <file> ``` 
or the older equivalent:
Code

   ``` git reset <file> ```
Replace <file> with the name of the file you wish to unstage. Unstaging all files.
Code  ``` git restore --staged ``` .
or the older equivalent:Code ``` git reset ```
These commands unstage all changes that have been added to the staging area, keeping the modifications in your working directory.
After unstaging, it is recommended to run git status to verify that the files are no longer in the staging area and are now listed as modified but not staged for commit.
 This allows for adjustments to the set of changes before creating a commit.