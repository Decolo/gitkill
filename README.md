using git commit --amend

     forward         backward             

1. git add .    |    git reset HEAD .    |    git rm --cached -r .
2. git add filename    |    git reset HEAD filename    |    git rm --cached filename

3. If you have made a commit but missed several files to be committed, you can add them, then use git commit --amend to modify previous committment.

4.  If you just want to undo the changes of some files, use git checkout -- filename. But be carefully to this action, cuz the changes will disapper, and files will go back to the last committed status. So every change you make, you've better to commit it!



