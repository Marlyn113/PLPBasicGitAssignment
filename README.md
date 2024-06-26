# PLPBasicGitAssignment
learning git and github
# PLPBasicGitAssignment

## Task 1: Repository Setup

### 1. GitHub Repository Creation

 Log in to your GitHub account.
 Create a new repository named `PLPBasicGitAssignment`.
 Initialize the repository with a README file.
 Create a new folder on your local machine named `PLPBasicGitAssignment`.
 Open a terminal or command prompt and navigate to the created folder.

cd path/to/PLPBasicGitAssignment
Initialize a new Git repository in your local folder.
git init
Link your local repository to the GitHub repository you created in Task 1.
git remote add origin your repository link
Inside your local folder, create a new text file named hello.txt and add a simple text message "Hello, Git!".
echo "Hello, Git!" > hello.txt
Stage the changes.
git add hello.txt
Commit the changes.
git commit -m "Add hello.txt with a greeting"
Push the committed changes to your GitHub repository.
git push -u origin master
