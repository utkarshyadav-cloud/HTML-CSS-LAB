Standard Lab Practical Experiment Format
Experiment No. 1

1. Experiment Title: Starting a Git Repository

2. Aim:
To start a Git repository for your lab folder and save your work with commits.

3. Software / Tools Required:

Visual Studio Code

Git Bash

GitHub Account (optional)

4. Theory:
Git is a distributed version control system used to track changes in source code. git init initializes a new repository, git config sets the user identity (name and email) for commits, git status shows the current status of files, git add stages files for commit, and git commit saves the changes with a message. git log shows the history of commits.

5. Algorithm / Procedure:

Create a folder named js-lab on Desktop

Open terminal in that folder and run git init

Set local name and email: git config --local user.name "Utkarsh Yadav" and git config --local user.email "your-email@gmail.com"

Verify with git config user.name and git config user.email

Create index.js with one http://console.log

Run git status, then git add index.js and git commit -m "Add home page"

Add second log in file and commit again with message "Add next meeting heading"

Run git log --oneline to see history

6. Program / Queries / Commands:
// Name: Utkarsh Yadav | Student ID: BCS2025381 | Ass: 1

console.log("Welcome to JS Lab");
console.log("Next Meeting at 10 AM");
Commands used:
git init
git config --local user.name "Utkarsh Yadav"
git config --local user.email "utkarsh@example.com"
git config user.name
git config user.email
git status
git add index.js
git commit -m "Add home page"
git log --oneline

7. Input:
Folder name: js-lab, File name: index.js

8. Output:

git config commands print the name and email you set

git status shows index.js as untracked before add

After commit it shows 1 file changed, 1 insertion(+)

git log --oneline shows 2 commits, newest first

Screenshot saved in images/ folder

9. Result:
Experiment performed successfully. Git repository was created, local config was set and two commits were saved successfully.
