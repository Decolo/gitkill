using git commit --amend

     forward         backward             

1. If you want to check the status of whole files' status in current diractory, use git status. Futhermore, if you want to know the specific difference between unstaged file and staged file, use git diff. In some cases, you've already staged some files and be willing to know the difference of the staged files and last committed files, use git diff --cached or git diff --staged. 


2. git add .    |    git reset HEAD .   

3. git add filename    |    git reset HEAD filename

4. If you get tired of the process of using git add ==> git commit, just use git commit -a -m msg to skip the action 'git add'.

5. git rm --cached -r . |    git rm --cached filename : If you need to remove some all or some files from remote repository without delete them from current directory.


6. If you have made a commit but missed several files to be committed, you can add them, then use git commit --amend to modify previous committment.

7.  If you just want to undo the changes of some files, use git checkout -- filename. But be carefully to this action, cuz the changes will disapper, and files will go back to the last committed status. So every change you make, you've better to commit it!



