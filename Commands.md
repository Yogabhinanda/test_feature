#Commands
Set global username and email for Git (Locally).
git config --global user.name "<your github username>"
git config --global user.email "<your email>"


Initialise an empty Git Repository
git init


Clone an existing Git Repository
git clone <repository URL>


Add file/stage to git
git add <filename>


Add all the files to git
git add .


Commit all the staged files to git
git commit -m "<your commit message>"


Restore the file from being modified to Tracked
git restore <filename>
git checkout <filename>


Show the status of your Git repository
git status


Show the branches of your git repository
git branch


Checkout to a new branch (Switch to new branch)
git checkout -b <branch name>


Checkout to an existing branch (Switch to branch)
git checkout <branch name>


Remove a branch from Git
git branch -d <branch name>


Show remote origin URL
git remote -v


Add remote origin URL
git remote add origin <your remote git URL>


Remove remote origin URL
git remote remove origin


Fetch all the remote branches
git fetch


Push your local changes to remote branch
git push origin <branch name>


Pull your remote changes to local branch
git pull origin <branch name>


Check your git commits and logs
git log
