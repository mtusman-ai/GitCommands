# Global Settings

git config --global user.name "Muhammad Usman"
git config --global user.email mt_usman@outlook.commands

# VS Code as Editor
code 
git config --global core-editor "code --wait"
git config --global -e

# end of line feeds (carriage return - \r, line feed - \n)
git config --global core.autocrlf true (input for Macbook)

# Create a directory
cd Documents/Git
mkdir project
cd project
ls
ls -a # to check hidden files

# Go to .git hidden folder
cd .git
ls 
cd .. # to go back to the repository

# Initlizing Git repository
git init

# Add to the file
-- ocean is to add text to the file1.md
echo hello > file1.md
echo ocean >> file1.md

# Check short status
git status -s

# name branch
-- branch is to list, create or delete branch. when used with -m (means move)
-- below command renames current branch to main branch
git branch -m main
-- create a new branch with the name Alpha
git checkout -b "Alpha"
