# Intern Portfolio - GitHub Practical Assessment
## Objective

The objective of this exercise was to practice Git and GitHub version control fundamentals using a real developer workflow. I created a local repository, committed files, connected it to GitHub, worked with feature branches, merged changes, and completed a Pull Request workflow.

## Tasks Performed

### Task 1 - Repository Initiation

Created the `intern-portfolio` folder and initialized it as a Git repository.

Commands used:

mkdir intern-portfolio
cd intern-portfolio
git init
git config --global user.name "Yogesh Gupta"
git config --global user.email "yogeshgupta12002@gmail.com"
git status




### Task 2 - Staging and Committing
Created:
index.html
about.txt
notes.md
Checked repository status and committed the files separately.
Commands used:
git status
git add index.html about.txt
git commit -m "Add initial portfolio files"

git add notes.md
git commit -m "Add project notes"

git log --oneline


Task 3 - Remote Repository Setup
Created a public GitHub repository named intern-portfolio and connected the local repository to GitHub.
Commands used:
git remote add origin https://github.com/yogesh12002/-intern-portfolio.git
git branch -m master main
git push -u origin main


Task 4 - Branching and Merging
Created the feature-update branch and added a Skills section to index.html and updated about.txt.
Commands used:
git checkout -b feature-update
git status
git add index.html about.txt
git commit -m "Update portfolio with skills and about information"
git push -u origin feature-update

git checkout main
git merge feature-update
git push origin main

Task 5 - Pull Request Workflow
Created the feature-contact branch and added contact.txt.
Commands used:

git checkout -b feature-contact
git add contact.txt
git commit -m "Add contact information"
git push -u origin feature-contact

Screenshots / Evidence

Task 1
<img width="497" height="28" alt="image" src="https://github.com/user-attachments/assets/2bf8f83e-7fb1-424f-914d-03aef4e5c973" />

Screenshot: Repository initialization and Git configuration.

Task 2
<img width="656" height="206" alt="image" src="https://github.com/user-attachments/assets/e2b3d880-0452-47ac-a3aa-2faaf960a09d" />

Screenshot: Git status, commits and commit history.

Task 3
<img width="468" height="160" alt="image" src="https://github.com/user-attachments/assets/7d9a9f36-8781-494a-b8ce-b4766b95ed4a" />

Screenshot: GitHub repository showing files and commit history.

Task 4
<img width="412" height="212" alt="image" src="https://github.com/user-attachments/assets/7a3d1ddd-9fa2-4944-af98-ce033270e653" />

Screenshot: feature-update branch, changes and merge into main.

Task 5
<img width="456" height="167" alt="image" src="https://github.com/user-attachments/assets/3abfa369-7080-4515-b7c4-dd024c688b5e" />
<img width="666" height="327" alt="image" src="https://github.com/user-attachments/assets/b21daa7a-daa7-4670-9753-72a2cc34f460" />

Screenshot: Pull Request from feature-contact to main and successful merge.
