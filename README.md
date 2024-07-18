# PLPBasicGitAssignment
Log in to your GitHub account:

Go to github.com and log in with your credentials.
Create a new repository:

Click on the + icon in the upper right corner and select New repository.
Fill in the repository details:

Repository name: Enter PLPBasicGitAssignment.
Description (optional): Add a brief description of your repository.
Public/Private: Choose whether you want your repository to be public or private.
Initialize this repository with a README: Check this box to automatically create a README file.
Create the repository:

Click the Create repository button at the bottom of the page.
After following these steps, your new repository PLPBasicGitAssignment will be created with an initial README file.
2. Local Folder Setup:
Create a new folder:

Create a new folder on your local machine and name it PLPBasicGitAssignment.
Open a terminal or command prompt:

Navigate to the newly created folder. For example, on Windows:
bash
Copy code
cd path\to\PLPBasicGitAssignment
On macOS/Linux:
bash
Copy code
cd /path/to/PLPBasicGitAssignment
3. Git Initialization:
Initialize a new Git repository:
In your terminal or command prompt, run the following command:
bash
Copy code
git init
This command will initialize a new Git repository in your local folder.
4. Connecting to GitHub:
Link your local repository to the GitHub repository:

First, add the GitHub repository as a remote repository. Run the following command, replacing <your-github-username> with your GitHub username:
bash
Copy code
git remote add origin https://github.com/<your-github-username>/PLPBasicGitAssignment.git
Verify the remote connection:

To ensure the remote repository has been added correctly, you can run:
bash
Copy code
git remote -v
You should see something like this:
bash
Copy code
origin  https://github.com/<your-github-username>/PLPBasicGitAssignment.git (fetch)
origin  https://github.com/<your-github-username>/PLPBasicGitAssignment.git (push)
After following these steps, your local folder will be set up, initialized as a Git repository, and connected to your GitHub repository.
Initialize a New Git Repository:

Run the following command to initialize a Git repository in your local folder:
bash
Copy code
git init
Step 2: Link Your Local Repository to GitHub
Add the Remote Repository:
Use the following command to link your local repository to the remote GitHub repository. Replace <your-github-username> with your actual GitHub username:
bash
Copy code
git remote add origin https://github.com/<your-github-username>/PLPBasicGitAssignment.git
Task 3: Making Changes
Step 1: Create a File
Create a New Text File:
Inside your local folder, create a file named hello.txt with a simple text message:
bash
Copy code
echo "Hello, Git!" > hello.txt
Step 2: Committing Changes
Stage the Changes:

Stage the new file using the following command:
bash
Copy code
git add hello.txt
Commit the Changes:

Commit the staged file with a meaningful message:
bash
Copy code
git commit -m "Add hello.txt with a greeting"
Task 4: Pushing to GitHub
Push the Committed Changes:
Push your local commits to the remote main branch on GitHub:

bash
Copy code
git push -u origin main
If you initialized the GitHub repository with a README or made changes directly on GitHub, and encounter any errors regarding unrelated histories, use the --allow-unrelated-histories option with git pull as previously explained.

Task 5: Verification
Verify on GitHub:
Open your web browser and go to your GitHub repository page.
Check that the hello.txt file is present in the repository, and confirm that the commit message "Add hello.txt with a greeting" is visible in the commit history.
