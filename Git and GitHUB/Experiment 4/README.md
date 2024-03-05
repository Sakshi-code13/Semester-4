# Editing a file and committing changes on GitHub

## About Commits

Similar to saving a file that's been edited, a commit record changes to one or more files in your branch. Git assigns each commit a unique ID, called a SHA or hash, that identifies:

• The specific changes

• When the changes were made

• Who created the changes


When committing, you must include a commit message that briefly describes the changes. You can also add a co-author on any commits you collaborate on. If the commits you make in GitHub Desktop are associated with the wrong account on GitHub, update the email address in your Git configuration using GitHub Desktop. Repository administrators can enable rulesets for a branch to enforce specific conventions when committing. For example, a ruleset can require a commit to be signed or an issue number to be referenced at the start of a commit message. GitHub Desktop will display a warning and prevent committing if a commit does not follow the rulesets.

Steps to make a commit on Git:

• Clone the repository: git clone <repository_URL>

• Navigate to the repository: cd <repository_name>

• Make changes to files.

• Check the status: git status

• Stage the changes: ' git add <file_name> ' or 'git add .'

• Commit the changes: git commit -m " Your commit message here " Push changes to the remote repository: git push origin <branch_name>

![download (2)](https://github.com/Sakshi-code13/Semester-4/assets/119587392/d89df207-e5ce-4917-aeae-51e5f0bb9188)

## Navigate 
[Experiment 4](https://github.com/Sakshi-code13/Semester-4/blob/Git-and-GitHub/Git%20and%20GitHUB/Experiment%204/Experiment%204.pdf)
