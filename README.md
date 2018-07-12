# git-rebase-test
A sample project to test git rebase
Steps taken
used rebase option

-> First select the parent of the commit you want to delete and use git rebase -i <commit hash code>
  
-> Select the line which you want to delete and replace pick to drop then save and exit by typing :wq

-> If there are any conflicts resolve them and add them.

-> use command git push -f to push it to remote.
