Q1. Global means it uses these settings anywhere in the coding-cafe folder.

Q2. ls -a shows even hidden files while ls only shows normal files. the .git appeared even though it does not appear with normal ls. 
The .git directory contains Git's repository data, including the commit history, configuration, and information Git uses to track the project.

Q3. Git is offering 4 untracked files/folders. The .DS_Store file is something I did not create as part of my coding work; it is a macOS system file.

Q4. After creating .gitignore, .DS_Store, __pycache__/ and *.pyc disappeared from the untracked list because it is now being ignored. The other project files and folders remain because they are files I want Git to track.

Q5. .gitignore should be committed because it contains the rules that tell Git which files to ignore. It needs to be shared with anyone else working on the repository so they follow the same rules.

Q6. README.md moved from "Untracked files" to "Changes to be committed." This happened because git add README.md moved it from the working directory into the staging area.

Q7. Git printed information showing that the commit was created, including the commit hash and the number of files changed. It said 5 files changed.
It printed:
[main (root-commit) 9345f74] Lab work so far
 Committer: Tejasveer Singh Pathania <tejaspathania@Tejass-Laptop.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 5 files changed, 55 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 README.md
 create mode 100644 lab04/notes.md
 create mode 100644 week02/lab01-log.txt
 create mode 100644 week02/notes.md


Q8. My commit hash is 9345f74. The first seven characters are the short version of the commit hash. They identify that particular commit and make it easier to refer to it without typing the entire hash.

Q9. The four steps are edit, stage, commit, and push. We edit our files, use git add to stage the changes, use git commit to save them in Git history, and use git push to send them to GitHub.

Q10. It gets a special name and a place as its a README file for users to read before opening code 

Q11.  It stored my account token locally so i dont need to re enter password.

Q12.The GitHub front page will show the contents of README.md as formatted text. GitHub automatically displays a repository's README on its front page because it is intended to introduce and explain the project.

Q13. It changed from head --> master to head -- > main, origin/main it didnt change my local history it just made it point to master instead of main

Q14. A private repository exists on GitHub but only the owner and people given permission can access it. If a repository does not exist on GitHub at all, there is no online repository for anyone to access or collaborate on.





