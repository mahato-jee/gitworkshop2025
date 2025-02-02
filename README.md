# gitworkshop2025
Name=Sandesh Mahato


# What is Git? 

Git is a version control system (VCS) that tracks changes in code. It is popular among developers worldwide, free, open-source, fast, and scalable.

# Uses of Git:

* Tracking the history of code changes.

* Collaboration among developers.

# What is GitHub?

 GitHub is a web-based platform built on top of Git. It provides hosting for Git repositories and additional features for collaboration, project management, and deployment.

# Key Terms:

* README file: Contains a project's description, features, and other details.

* Repository (repo): A folder that contains your project's files.

* Add (staged): To start tracking a new or modified file.

* Commit: To finalize the changes after adding.

* Untracked file: A new file not tracked by Git.

* Modified file: A file with changes that haven't been committed.

* Staged: A file ready to be committed.

* Unmodified file: A file with no changes.

# Getting Started with Git:

1. Download Git: Install Git on your PC.

2. Configure Git in the terminal:

bash

git config --global user.name "your name"

git config --global user.email "example@email.com"

git config --list

# Basic Commands:

1. Clone and Status:

* Clone: Duplicate a repository from a remote repo to your local machine.

bash

git clone <repository-link>

* Status: Display the status of code.

bash

git status

2. Add and Commit:

* Add (stage): Add new or modified files from the working area to the Git repository.

bash  

git add .    # Add all files

git add <file-name>   # Add specific file

* Commit: Record changes or modifications.

bash

git commit -m "meaningful title"

3. Push:

* Push: Upload local repository content to the remote repository (e.g., GitHub).

bash

git push origin
