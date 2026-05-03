# Undoing Changes

# Git Reset

- It is used to undo commits or changes by moving the HEAD and current branch pointer to a specific commit.
- It can also modify the staging area and working directory depending on the options used.

  Types of Reset:

  1. --soft: moves Head, but keeps changes staged. Use when you want to undo a commit but keep the changes for a recommit.
          `git reset --soft <hash>`
  
  2. --mixed(default): moved Head and unstage changes, keeping changes in the working directory.
            - use when you want to undo staged changes.

      - Unstage a Specific File: 
            -  To unstage a specific file, keeping your changes in the working directory 
            - `git reset <file-name>`
    
      -  Unstage All Files: To unstage all files, 
            - This will remove all files from the staging area, but keep your changes in the working directory.
            - `git reset`
         ### Example
            - staged file --> not staged

  3. --hard: moved HEAD and discard all changes (both staged and working directory)
     
        - This command will remove all changes after the specified commit, including those in the working directory.
        - `git reset -- hard <commit-hash>`
        


## Case 2 : Undo commited changes (for one commit)

1. Reset to the Previous Commit:
    - To undo the last commit while keeping changes in the working directory (useful if you want to edit or re-commit)
    - This command moves the current branch pointer back by one commit.
    - The changes from the undone commit will be left in your working directory and staging area.
    - `git reset HEAD~1`

### Example

 
- To view all the commits: `git log`

  

# Git Revert

- Undo a Commit Without Losing History
- git revert creates a new commit that undoes the changes made by a previous commit.
- Unlike git reset, it preserves the commit history, making it ideal for collaborative workflows
- `git revert <commit-hash>`

# Git Ammend

   - ` git commit --amend -m "meesage" `
   - It is used to modify the most recent commit - either by changing the commit message or by including new changes in      it.


# Git Staged

- Should you decide not to commit the change, the status command will remind you that you can run git restore --staged command to unstage these changes.

<img width="" height="" alt="image" src="https://github.com/user-attachments/assets/b85cabf1-9fa9-43b9-ac0f-9aa3e9ea8d62" />


