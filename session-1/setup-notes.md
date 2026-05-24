# THE 3 GIT STAGES EXPLAINED IN MY OWN WORDS

## 1. Working directory:
The working directory is the place where I work on my project files directly. 
This is where I create new files, edit code, delete files, or make any changes I want.
It contains the current version of the project that i'm working on before Git officially tracks the changes.

## 2. Staging Area (Index):
The staging area is like a waiting area for my changes before I save them into Git. After editing my files, I choose the 
specific changes I want Git to save by adding them to the staging area. I use git add . to add all files or git add 
<file_name> to add a specific file


## 3. Repository (.git folder):
The repository is where Git permanently saves my project history. When I commit my changes, Git stores them inside the .git 
folder. This allows me to keep track of old versions of my project, go back to previous work if needed, and see all the 
changes I have made over time. I use git commit -m "commit message" to save a snapshot to the .git folder


