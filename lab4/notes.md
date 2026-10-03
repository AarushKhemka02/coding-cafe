# Coding Café — Lab 4 Notes

## Question 1

`--global` means the Git setting applies to all repositories for my user account on this computer. If I left it out, the setting would only apply to the current repository.

## Question 2

`ls -a` showed the hidden `.git` directory, which did not appear with normal `ls`. The `.git` directory contains Git's repository information, including its history and configuration.

## Question 3

Git was offering a small number of files and folders to track at this stage. The `week02/` folder contained my lab work, while `.DS_Store` was macOS system metadata rather than something I had written.

## Question 4

After creating `.gitignore`, the files and folders matching its rules disappeared from `git status`. This included `.venv/`, `__pycache__/`, `*.pyc`, and `.DS_Store`.

## Question 5

`.gitignore` itself should be committed because it is part of the repository and tells Git which files to ignore. The files listed inside it are ignored, but the `.gitignore` file itself needs to be tracked and shared.

## Question 6

`README.md` moved from the Untracked files section to Changes to be committed after I ran `git add README.md`. In the three-places model, this means the file moved from the working tree to the staging area.

## Question 7

Git printed that 2 files were changed, with 4 insertions. The commit recorded the addition of `.gitignore` and `README.md`.

## Question 8

The first seven characters of my commit hash are `149c904`. They are the short form of the commit hash and identify that specific commit in Git's history.

## Question 9

The four steps are checking `git status`, staging the file with `git add`, saving the changes with `git commit`, and checking the history with `git log`.

## Question 10

`README.md` gets a special name and place because GitHub automatically displays it on the repository's front page. It acts as the main introduction and guide to the project.

## Question 11

`gh auth login` authenticates my GitHub account with the GitHub CLI and stores the authentication information. This means GitHub can recognize me when I push without asking for my password each time.

## Question 12

The `README.md` file is shown on the front page because GitHub automatically renders a repository's README as its main introductory page.

## Question 13

No, pushing did not change my local history. `git push` copied my existing local commits to GitHub; it did not create a new commit.

## Question 14

A private repository exists on GitHub but only people with permission can access it. If the repository did not exist on GitHub at all, there would be no online copy of the project for anyone to access.
