# git add:

- this will add all of the work or the code to the staging area which is ready to be go into the github repo.

`git add file_name` 

- this will add the particular file to the staging area.

` git add . ` 

- this will add the all files to the staging area.

` git rm --cached <file_name> `

- this will take the file from staged to unstaged.

# git commit:

` git commit -m "some message" `

` git commit -am "some message" ` : will add and commit.

- To update the msg to commit:
  
`  git commit --amend -m "some message with add" `

  

# git history:

- we can see the history of our work using: ` git log `
- to gee graph do:  ` git log -all --graph `
- to see everything :
  
` git log --all --pretty=format:"%h %cd %s (%an)" --since="7 days ago" `
  
- most suitable:
  
` git log --pretty=format:"%h %ad | %s%d [%an]" --date=short `
 
  <img width="569" height="424" alt="image" src="https://github.com/user-attachments/assets/2af4a964-f392-4ba6-adfc-df6fd4fb9437" />

  

  <img width="589" height="619" alt="image" src="https://github.com/user-attachments/assets/1e38b821-dd1c-4c18-abf2-5175b7ddc577" />
  
` gitK `
- to explore the changes (it will open the git GUI)

# git Diff

- ` git diff commit1 commit2 `
- It is used to show the difference between working dir and staging area.

  



  













