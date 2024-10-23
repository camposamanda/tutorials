## 1) Create your local repository

- choose where you want to set your local repository in your computer, and create a folder. Each project has to have it's own folder. If you plan to use github to sync more than one project do not put it all together in the same folder. For now, just go ahead and create a folder called something like 'my-project-name_github' if you feel it would be easier to rememember this is a github synced folder.
- add at least one file to this folder, we will use it as an example in step 3 and 5.

## 2) Create your remote repository

- log in to your github account in would browser
- in the top left corner click in 'repositories'
- on you are in your repository page go to the top rigth corner and click on 'new'
- create a repository name, and check it as 'PRIVATE' if you do NOT want to make your files visible to everyone.
- you can create a README.md file later, first lets get into your first commit!
- it will show you instructions on how to sync it with your local repository for your first commit. Keep this tab open in your browser.

## 3) Create your .gitignore file

- go to [this website](https://www.toptal.com/developers/gitignore/) to create it for you
- once in this website in the 'create space' add all the file formats you know you are using in this folder. Do not overthink it, you can add just one (the format of the file from step 1) and move forward!
- once you click on add, a new tab will open. Copy the content and paste it in you text editor of preference. Save it as '.gitignore' in your local repository.
**Pro tip: In the last line include all the folders you do NOT wish to sync with your remote repository. They will remain hidden from your sync. It should be in the format 'my_hidden_folder_name/'**
- use Ctrl+h to reveal the .gitignore file in your local computer

## 4) Connect your local and remote repositories FOR THE FIRST TIME

We will use the instructions on the "... or create a new repository on the command line" in the tab you created your remote repository

- go to your local repository and open it in the terminal
- use the 'git innit' command to initialize as a github folder
- use 'git status'and note that there are 2 files in your local repository that are not synced. However we will sync just one first.
- use 'git add .gitignore' to add your first file
- use 'git status' to check that your first file has been staged to be synced with the remote repository
- use 'git commit -m 'this is my first commit' ' to commit the staged file
- use 'git branch -M main' to create a main branch (do not need to worry about that right now, but branching is one of the coolest thing on git)
- use 'git remote add origin https://github.com/your-user/your-folder-name.git'. Remember to use the equivalent line from your own remote repository, if you copy-paste this one it won't work!
- once you are ready, use 'git push -u origin main' to push your local file into the main branch of your remote repository.

This is all you need to know for your FIRST COMMIT ever in a new remote repository! The following ones are simpler and straigth forward.

## 5) you are all set to sync all the other files!

- go to your local repository and open it in the terminal
- use 'git status' to check that there is still a file to be synced in your locar repository (the one we added in step 1)
- use 'git add your_file.xx' to stage it to be synced
- go ahead and use 'git status' again, you will see your file is staged to be synced now
- use 'git commit -m 'this is my second commit' ' to commit the staged file
- once you are ready, use 'git push' to push your local file to your remote repository

## TA-DA!

*You are all set!*

Refer to this quick demo as much as you need when creating new repositories in your github :)

