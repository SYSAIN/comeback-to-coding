

 **Git Basics Cheat Sheet**


---
# 1️⃣ Installing Git
---
Visit the Git for Windows page and click "Download".

Follow the installation instructions and accept default settings.

After installing, open Git Bash or Command Prompt and check installation:

`git --version`

---

-------------------------------
# 2️⃣ Git Configuration
-------------------------------
Set your username and email:


`git config --global user.name "Your Name"`

`git config --global user.email "youremail@example.com"`

-------------------------------
# 3️⃣ Starting a Repository
-------------------------------
Create a new folder for your project:

`mkdir my-project`

`cd my-project`


Initialize Git:

`git init`


-------------------------------
# 4️⃣ Basic Git Workflow
-------------------------------

Check the status of your repo

`git status`


Add files to staging

`git add filename`

`git add .`  Adds all files


Commit your changes

`git commit -m "Initial commit"`


See commit history

`git log`


-------------------------------
# 5️⃣ Working with Remote Repositories
-------------------------------

Add a remote repo

`git remote add origin https://github.com/username/repo.git`


Push changes

`git push -u origin main`
 
 or

`git push -u name_of_the_new_branch`

Pull changes

`git pull origin main`


-------------------------------
# 6️⃣ Branching
-------------------------------

Create a new branch

`git branch new-branch`


Switch branches

`git checkout new-branch`

`git switch`

Rename current branch

`git branch -M new-name`


Merge branch into main

`git checkout main`

`git merge new-branch`

Switch to new branch 

`git switch new-branch`


<<<<<<< HEAD:git-knowledge/git_essential_commands.md
" -------------------------------
" 7️⃣ Handling Conflicts
" -------------------------------

=======
-------------------------------
# 7️⃣ Handling Conflicts
-------------------------------
>>>>>>> main:git-knowledge/Git-basics.md
If there is a conflict, Git marks it in files:

<<<<<<< HEAD

Your local changes
Remote changes

>>>>>>> branch-name


Edit the file to keep what you want.

Then add and commit:

`git add filename`

`git commit -m` "Resolved conflict"


-------------------------------
# 8️⃣ Deleting Files and Directories
-------------------------------

Delete a file:

`rm filename`


Delete a folder (use carefully!):

`rm -rf foldername`

