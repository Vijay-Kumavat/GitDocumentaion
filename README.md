# Git Documentation


What is Git & github ?


Why do we use git and github ?

Git is a version control system that lets you manage and keep track of your source code history.

GitHub is a hosting site where developers and programmers can upload the code they create and work collaboratively to improve it. A defining feature of GitHub is its robust version control system. The version control lets coders tweak software—potentially fixing bugs or improving efficiency—without affecting the software itself or risking the experience of any current users. Proposed changes can be easily merged into the live software after the proposals are reviewed and approved.

**Process**
   
   *Method 1 :*
        
                Create a new project.
                Open the project in vs code.
                Clone the repositories (with a new folder, then start the implementation).
                
   *Method 2 :*
                
                Open the existing project in vs code.
                Open the git bash in the new terminal.
                Git important command : git --help.
                Run the following git command.
                git init : Create an empty Git repository or reinitialize an existing.
                git add . : Add file contents to the index
                git status : Show the working tree status
                git commit -m ‘<commit>’ .  : Record changes to the repository
                git branch -M <branch>. : List, create, or delete branches
                git remote add origin <url>.
                git push -u origin <branch>.
                
   *Git command :*

               git checkout -b <new_branch> : Create the new branch
               git checkout <branch> : Switch the branch
               git branch -d  <branch> : Delete the branch
               git add <file> : Add the changing file into staging.
               git commit -m <commit> . : commit the staging files.
               git push origin <branch> : push the changes into the selected branch.
               git config --get remote.origin.url : Check the clone url
               git push origin <branch> --force : push the changes forcefully.
               git add --all : all files are added in the staging section.
               git log : find the author and insert date time.
               ?? - Untracked files
               A - Files added to stage 
               M - Modified files 
               D - Deleted files
Git commands : 


Important links of gits commands : 
https://github.com/git-guides/
https://www.c-sharpcorner.com/article/managing-files-on-github-using-git-bash-in-real-time-scenario-know-about/



Error List : 
fatal: Unable to create 'C:/Users/vijay/OneDrive/Desktop/All.Code/Angular/AngularOne/.git/index.lock': File exists.
rm -f ./.git/index.lock



