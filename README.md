# VCC_Assignment_1_Fausto

This repository contains Assignment 1 and is my first repository for this course. It builds on my existing experience with Git and GitHub by reinforcing version control concepts and workflows through hands-on practice.

## What I Learned

- The basics of version control and how it records changes to files over time.
- The difference between Git, which tracks changes locally, and GitHub, which hosts repositories online and supports collaboration.
- How to add files to the staging area and commit changes to a local repository.
- How to use a `.gitignore` file to exclude files that should not be tracked by Git.
- How to add a license and a `README.md` file to a repository.
- How to clone a GitHub repository to my computer, modify files locally, stage and commit changes, and push those commits back to GitHub.

## Git File States and Workflow

Git uses three main states to track changes:

| State | Description |
| --- | --- |
| Modified | Changes exist in the working directory but have not been staged. |
| Staged | Changes have been selected for the next commit using `git add`. |
| Committed | Staged changes have been saved as a snapshot in the local repository using `git commit`. |

A new file starts as **untracked** until it is added to Git.

### Basic Workflow

1. **Edit** a file in the working directory.
2. **Stage** its changes: `git add filename` or `git add .Markdown Preview EnhancedMarkdown Preview Enhanced: Open Preview`
3. **Commit** the staged changes: `git commit -m "Describe the changes"`
4. **Push** local commits to GitHub: `git push https://github.com/fausto-gonzalez/VCC_Assignment_1_Fausto.git`

**Note:** Pushing synchronizes commits with the remote repository; it is not another file state. A commit already records changes locally before they are pushed.

## Why Version Control Matters

Version control helps us maintain a clear history of changes, recover earlier versions of files, and collaborate without losing track of each person's contributions. It is important in software development and in other industries where people work with documents, designs, and other files that change over time.

## Author

Fausto Gonzalez
