interview questions GIT ?

What is the difference bw Git fetch and git clone ?
Ans > 
git clone : The git clone command is used to create a copy of a remote Git repository on your local machine. When you clone a repository, you create a complete copy of the project, including all its branches, commit history, and files.
Ex : git clone <repository_url>

Git fetch : git fetch means we can get updated git status on our local repo
ex : git fetch origin

How to rewrite the git file after puched to git ? and now i need to edit some update ?

1.switch the branch you want to edit 
 git checkout <branch name >
2.Edit the file you want 
add modified file to the stagging area 
git add <file_name>
git commit -m "Your commit message describing the changes"
git push origin <branch_name>

