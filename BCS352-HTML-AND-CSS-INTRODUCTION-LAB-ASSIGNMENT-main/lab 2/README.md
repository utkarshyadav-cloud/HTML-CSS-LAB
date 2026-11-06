STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 2

Experiment Title: Pushing and Cloning a Repository

Aim:

To send your commits to a second repository on your computer and make a copy of it with clone.

Software / Tools Required:

1. Visual Studio Code
2. Git Bash
3. File Explorer

Theory:

git init --bare creates an empty bare repository that acts like a remote server (like GitHub but on your own PC). git remote add origin path links your main lab folder to that remote. git push origin main sends all your commits to the remote. git clone remote new-folder makes a complete copy of the remote repository with full history.

Algorithm / Procedure:

1. Open terminal inside js-lab folder.
2. Create bare repo next to it using git init --bare ../js-remote
3. Add it as origin using git remote add origin ../js-remote
4. Check remote using git remote -v
5. Push commits using git push origin main (if branch is master then use master).
6. Go one folder back using cd ..
7. Clone remote into new folder using git clone js-remote js-copy
8. Go into js-copy and run git log --oneline to verify.

Program / Queries / Commands:

Name: Utkarsh Yadav | Student ID: BCS2025381 | Ass.: 2

Commands Used:

1. cd js-lab
2. git init --bare ../js-remote
3. git remote add origin ../js-remote
4. git remote -v
5. git push origin main
6. cd ..
7. git clone js-remote js-copy
8. cd js-copy
9. git log --oneline

Input:

1. Existing folder: js-lab with 2 commits from Assignment 1.
2. Remote folder to be created: js-remote.
3. Clone folder to be created: js-copy.

Output:

1. git remote -v shows:

origin  ../js-remote (fetch)
origin  ../js-remote (push)

2. git push ends with line: main -> main or master -> master.

3. git clone shows Cloning into 'js-copy'... done.

4. git log --oneline in js-copy shows the same 2 commits as in js-lab.

Screenshot saved in images/ folder.

Result:

Experiment performed successfully. Remote repository created, commits pushed to origin and repository cloned successfully with the same history.