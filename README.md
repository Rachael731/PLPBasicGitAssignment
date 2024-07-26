# PLPBasicGitAssignment
Task 1: Repository Setup

1. GitHub Repository Creation:
I logged into my  GitHub account and created a new repository on GitHub "PLPBasicGitAssignment".

Task 2: Local Setup
2. Local Folder Setup:
I navigated to the Desktop using command cd Desktop then craeted a new directory using command mkdir PLPBasicGitAssignment and navigated inside this folder.

3. Git Initialization:
I used the command git init to initatialize a new Git repo on the local folder.

5. Connecting to GitHub:
I then linked the local repo to the GitHub repository created in Task 1 using the command git add origin [https://github.com/Rachael731/PLPBasicGitAssignment.git](https://)

Task 3: Making Changes
5. Create a File and Commit Changes:
I created a new txt file on the local folder using command touch hello.txt and commited the changes using command git commit -m "Hello, Git!" 

Task 4: Pushing to GitHub
7. Pushing to GitHub:
I pushed the committed changes to GitHub uwing the command $ git push -u origin master
because the branch name was master, and the command git push -u origin main had not worked in the three previous instances I had tried to complete the assignment.

I used the command code . to open VS Code but I still had trouble with the branch name master. I used several commands to sort the issue; 
git fetch origin
git rebase origin/main
git rebase --continue
git push -u origin main

Task 5: Verification
I verified the GitHub repo and confirmed that the `hello.txt` file and commit message are visible.

Documentation:
I documented the steps taken to complete the assignment then I will commit, pull, and push the changes back to GitHub but I got a message that everything was up-to-date. I opted to document the changes directly on GitHub and commit the changes over here. 

Overall; I had a difficult time completing this assignment because of the difference in the branch names main and master.
