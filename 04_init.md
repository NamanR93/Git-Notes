# init

- The git init command is used to initialize a new Git repository in the current directory or in a specified directory.
- When you run git init, Git creates a new subdirectory named .git that contains all of the necessary files for the repository. 
- These include the Git database for tracking changes, configuration options, and a few other bits and pieces to manage the repository.
- `git init`

## Workflow : Pushing a project from local to remote repo on github

1. Create or Navigate to a Directory: If starting a new project, create a directory for it or navigate to an existing project directory.
2. Run git init: Initialize the Git repository: `git init`.
3. Add Files and Make Initial Commit: After initializing, you can start adding files to the repository, stage them, and make your first commit:
   `git add .`
   
   `git commit -m "Initial commit"`
5. Create a new repo on github
6. Run: `git remote add origin <- link ->`
   - The git remote add origin <url> command is used to link your local Git repository to a remote repository.
   - This allows you to push and pull changes between your local repository and the remote repository.
   - `git remote -v` : to verify remote
   - `git branch` : to check branch
7. `git push origin main` 
