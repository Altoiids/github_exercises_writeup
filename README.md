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
# reading the text we will get to know conflict is in equation.txt file
nano conflict.txt
# resolve the conflict by making entire text 2 + 3 = 5
git add A.txt   # for adding file to staged area
git commit -m "gitignore file add" # for committing the file
git verify # for pushing the file
</pre> 
