# Push

- The git push command is used to upload (or push) your local repository changes to a remote repository (e.g., GitHub, GitLab, Bitbucket). 
- After you commit changes locally using git commit, you can share them with others by pushing them to the remote repository.
- `git push <remote> <branch>`
  
  remote: The name of the remote repository (typically origin by default).
  
  branch: The branch you want to push changes to (e.g., main, master, or feature-branch).

- Example: `git push origin main` : Pushes the local `main` branch to the `origin` remote repository.
  
- We can check the name of the remote as well using  ` git remote `
- Nd to check URL of remote :  ` git remote -v `

## Common Use Cases:
1. First Push (after cloning or creating a new repository):
   
   - `git push -u origin main` : Sets the upstream branch and pushes changes to the remote repository.
   - The -u option sets the upstream branch, so future pushes can be done with just `git push` without needing to specify the branch.
     
2. Regular Push (after commits): Once the upstream branch is set, you can just run:
   

   - `git push`

