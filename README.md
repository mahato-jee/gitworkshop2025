# gitworkshop2025
Sandesh Mahato
What is Git?
Git is a version control system, which is software used to track changes in code.

Purpose: To manage code versions efficiently.
Key Features:
Popular among developers worldwide.
Free and open-source.
Fast and scalable.
Uses of Git:

To track the history of code.
To facilitate collaboration among developers.
What is GitHub?
GitHub is a web-based platform built on top of Git.

It hosts Git repositories and provides additional features for:
Collaboration.
Project management.
Deployment.
Keywords and Their Meanings:
README File: A file containing the description, features, and details about a project.
Repository: A folder where project files are stored and managed.
Add (Staged): Marks a file to be tracked by Git after making changes. It’s the first step after modifying files.
Commit: Finalizes the changes made to files. It’s the second step after adding files.
Untracked File: A file that Git is not yet tracking.
Modified File: A file that has been changed or updated.
Staged File: A file ready to be committed (added).
Unmodified File: A file with no changes.
Steps to Set Up Git on Your Computer:
Download Git and install it.
Configure Git in the terminal using the following commands:
git config --global user.name "Your Name"
git config --global user.email "example@email.com"
To check the configuration:
git config --list
Basic Git Commands (Step-by-Step):
1. Cloning a Repository
Purpose: To create a duplicate of a remote repository on your local machine.
Command: git clone <repository-link>
2. Checking Status
Purpose: Displays the current status of your code (e.g., untracked, modified, staged).
Command: git status
3. Adding Files
Purpose: Moves untracked or modified files to the staging area.
Commands:
To add all files: git add .
To add a specific file: git add <file-name>
4. Committing Changes
Purpose: Records changes made to files in Git’s history.
Command: git commit -m "Meaningful message"
5. Pushing to a Remote Repository
Purpose: Uploads local repository changes to a remote repository (e.g., GitHub).
Command: git push origin
This sequence ensures a smooth workflow from local changes to collaboration on GitHub.








