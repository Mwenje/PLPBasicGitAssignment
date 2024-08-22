1. GitHub Repository Creation:

  - Log in to your GitHub account.

  - Create a new repository on GitHub called PLPBasicGitAssignment

  - Initialized it with a README file.



Task 2: Local Setup

2. Local Folder Setup:

  - Created a new folder on your local machine PLPBasicGitAssignment

  -cd PLPBasicGitAssignment command to navigate to the created folder.



3. Git Initialization:

  -git init command to Initialize a new Git repository in your local folder.



4. Connecting to GitHub:

  - Link your local repository to the GitHub repository you created in Task 1.

   ```

git remote add origin https://github.com/Mwenje/PLPBasicGitAssignment.git

   ```


Task 3: Making Changes

5. Create a File:

  -  created a new text file `hello.txt` with a simple text message "Hello Day4 assignement1".
    echo "Hello Day4 assignement1" >hello.txt

6. Committing Changes:

  - Staged the changes.

 git add hello.txt
-commited the changes

$ git commit -m "Add hello.txt with a greeting"

7. Pushing to GitHub:

  - Push the committed changes to your GitHub repository.
git push -u origin main

it brought some errors and after some research i used
 git push origin main --force
to overwrite the remote branch with your local changes.
