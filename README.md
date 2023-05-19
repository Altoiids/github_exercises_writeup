# github_exercises_writeup
# Challenge 1- master 

## Commands Used
<pre>git verify
</pre> 

# Challenge 2- commit-one-file 
## Commands Used
<pre>
git add A.txt   # for adding file to staged area
git commit -m "file A chosen" # for committing the file
git verify # for pushing the file
</pre> 

# Challenge 3- commit-one-file-stagged 
## Commands Used
<pre>
git reset A.txt   # to remove A.txt file from stagging are
git commit -m "file A removed" # for committing the file
git verify # for pushing the file
</pre> 

# Challenge 4- ignore-them
## Commands Used
<pre>
touch .gitignore   # to create .gitignore file
nano .gitignore # to edit content of .gitignore file
 {  *.exe
   *.o
   *.jar
   /[Ll]ibrary/ } - content of .gitignore file
git add A.txt   # for adding file to staged area
git commit -m "gitignore file add" # for committing the file
git verify # for pushing the file
</pre> 

# Challenge 5- chase-branch
## Commands Used
<pre>
git merge chase-branch
git verify # for pushing the file
</pre> 

# Challenge 6- merge-conflict
## Commands Used
<pre>
git merge another-piece-of-work
# reading the text that has appeared we will get to know conflict is in equation.txt file
nano conflict.txt
# resolve the conflict by making entire text 2 + 3 = 5
git add equation.txt   # for adding file to staged area
git commit -m "gitignore file add" # for committing the file
git verify # for pushing the file
</pre> 

# Challenge 7- save-your-work 
## Commands Used
<pre>
git stash #to save work on side and continue later.
nano bug.txt #open file and fix the bug
git add bug.txt
git commit -m "bug fix"
git stash pop
nano bug.txt #add the given statement at the end
git add bug.txt program.txt
git commit -m "stash learn"
git verify
</pre> 

# Challenge 8- change-branch-history 
## Commands Used
<pre>
git rebase hot-bugfix #to change the commit history. moving a branch from one position to other
git verify
</pre> 

# Challenge 9- remove-ignored
## Commands Used
<pre>
git rm ignored.txt
git commit -m "file removed"
git verify
</pre> 

# Challenge 10- case-sensitive-filename 
## Commands Used
<pre>
git mv File.txt file.txt
git add file.txt
git commit -m "file name changed"
git verify
</pre> 

# Challenge 11- fix-typo 
## Commands Used
<pre>
nano file.txt #make the changes
git add file.txt
git commit --amend -m "typo remove"
git verify
</pre> 

# Challenge 12- forge-date 
## Commands Used
<pre>
GIT_COMMITTER_DATE="mention date" git commit --amend --no-edit --date "mention date" #will change the date
git log #to check if we did write
git verify
</pre> 

