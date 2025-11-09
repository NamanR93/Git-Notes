# Git Merge VS Git rebase

## Git Merge

- git merge combines two branches by creating a new "merge commit." It maintains the full history of both branches.

### Example: Merging feature into main

`git checkout main`

`git merge feature`

### Result

![image](https://github.com/user-attachments/assets/7d775146-4832-4b3e-a834-c78746ef487f)

- A merge commit (M) is created to join the branches.
- The history remains non-linear (branches remain visible).

Pros of Merge:

✅ Preserves history (useful for tracking changes).

✅ Safer for shared branches (used in team workflows).

✅ Easy to undo with git revert.

Cons of Merge:

❌ Can create messy history with too many merge commits.

❌ Harder to follow when multiple merges occur.


## Git Rebase

- Rewrites History
- git rebase moves commits from one branch on top of another, rewriting history.

### Example: Rebasing feature onto main

`git checkout feature`

`git rebase main`

### Result

![image](https://github.com/user-attachments/assets/9711fc0a-6684-420c-98c9-51e663fae56e)

- Instead of a merge commit, D and E are rebased onto main.
- No merge commit is created.
- The history becomes linear and clean.

Pros of Rebase:

✅ Cleaner history (avoids unnecessary merge commits).

✅ Easier to understand (history looks like a straight line).

✅ Works well for feature branches before merging.

Cons of Rebase:

❌ Rewrites history (dangerous on shared branches).

❌ Can be complicated if conflicts occur in multiple commits.

❌ Harder to undo (git reflog is needed to recover lost commits).

## Use Case


![image](https://github.com/user-attachments/assets/13807045-1f1c-4fe8-a36d-014a3c058eb5)

