# Merge
- merging code: there are two ways to do it:
1. using merge command          
- `git diff <branch-name> ` : to compare commit, branches, files and more.
- ` git merge <branch-name> ` : to merge two branches.
2. By creating a PR (pull request)


# Pull
- ` git pull origin main ` : combo of Fetch + Merge.
- Used to fetch the content from a remote repo and immediately update the local repo to match the content.

# Fetch
- It downloads the updates from remote repo without changing your working branch.
- Lets you review changes before merging.
- After fetching, you can use git merge or git diff to inspect and apply the changes. 
