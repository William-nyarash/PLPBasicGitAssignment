# Documentation: PLPBasicGitAssignment Repository Setup

##  This documentation guides you through setting up a local Git repository and linking it to a remote GitHub repository.


### Task 1: Repository Setup
1. `GitHub Repository Creation`
- Log in to your GitHub account.
- Create a new repository on GitHub named "PLPBasicGitAssignment" and initialize it with a README file.

### Local Setup
2. `Local Folder Setup
Create a new folder on your local machine named` "PLPBasicGitAssignment"
- Open a terminal or command prompt and navigate to the created folder.
### 3. Git Initialization
- Initialize a new Git repository in your local folder with the command:

```bash
git init
```

### 4. Connecting to GitHub
- Link your local repository to the GitHub repository you created in Task 1 with the command:

```bash
git remote add origin <repository-url>
```

*Replace <repository-url> with the actual URL of your GitHub repository.*

## Task 2: Making Changes
### 5. Create a File
- Inside your local folder, create a new text file named hello.txt.
- Add a simple text message, such as *"Hello, Git!"*.

### 6. Committing Changes
- Stage the changes with the command:
```bash
git add hello.txt
```

- Commit the changes with the command:
bash

```bash
git commit -m "Add hello.txt with a greeting"
```

## Task 3: Pushing to GitHub
## 7. Pushing to GitHub
- Push the committed changes to your GitHub repository with the command:

```bash
git push -u origin main
```

## Task 4: Verification
### 8. Verify on GitHub
- Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.


#### thank you for stoping by.&copy;waren