# Fork

- Forking is a way to create a personal copy of someone else's repository under your own account. 
- This copy allows you to freely experiment with changes without affecting the original project. 
- After making changes in your fork, you can propose these changes to be merged back into the original repository through a pull request. 
- Forking is commonly used in open-source projects where contributors want to work on features or fixes independently before merging them into the main project.
  
### Key Concepts:

- Forking: Creating a copy of a repository under your GitHub account. This copy is completely independent of the original repository, allowing you to make changes without affecting the original project.

- Pull Request: After making changes to your forked repository, you can propose those changes to the original repository by creating a pull request. This allows the maintainers of the original repository to review and merge your changes.

## How to Fork a Repository on GitHub:

- On the top right of the repository page, click the "Fork" button. This creates a copy of the repository under your GitHub account.

  Demo:
     - create one repo in one account and fork it using another.
	   - Now do some changes in parent repo, then to bring those in child(forked one) , we do sync  fork button.
   - Now we will see, how we can contribute to main branch using forking.
	    - we have clone the repo(Namans one), create feature branch , commit changes and push it.
	    - Now create the PR for the owner(Numun) to review it and merge the changes.
	    - Now go to Numuns account , review the PR and merge the changes. Also sync  fork the changes to Namans as well.

# Tags

  - are the references used to mark the specific points in repo history.
  - often used to label release versions.
  - there r two types of tags : lightweight and annotated tags.
  - create a  lightweight tag using
    <img width="499" height="103" alt="namanrawat@Namans-MacBook-Air Forking-demo   git tag v1 0 0" src="https://github.com/user-attachments/assets/a5d615bc-7c7a-4f54-b14a-8a846bc1c2b4" />

   - Annotated tag:
          <img width="589" height="158" alt="namanravat@Nanans-MacBook-Air Forking-deno   git tag -a v1 0 1 -n Release v1 0 1" src="https://github.com/user-attachments/assets/a1472ea6-6644-4146-b7be-62baed2be8b9" />

<img width="670" height="367" alt="1 6 6 vl" src="https://github.com/user-attachments/assets/983764b8-5ce2-49c0-ab7e-e732b9a63269" />

￼
 - To see all tags: ` git tag `
 - to read about the tag : ` git tag -v v1.0.1 `
