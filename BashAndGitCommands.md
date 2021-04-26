# **Bash and Git Commands**
## **Bash Commands**

- cd = moving to the home directory
- cd 'directory name' = moving to a specific directory
- cd .. = moving up a directory
- ls = listing the contents of the current directory
- ls -a = listing the contents of the current directory, plus hidden files
- pwd = printing the working directory
- mkdir 'directory name' = making a new directory
- touch 'file name' = creating a new file with a specific name
- echo 'String' = printing text to the console
- echo 'String' > myTextFile.txt = writing String to the file specified
- nano 'file name' = opening nano to edit the file, can also use vim
- mv 'file' 'location' = moving files and folders
- mv 'file name' 'new file name' = renaming files and folders 
- cat 'file name' = reading a file
- rm 'file name' = removing a file
- rmdir 'directory name' = removing/ deleting an empty directory
- rm -rf 'directory name' = removing/ deleting a directory that is not empty (-r = recursively and -f means forcefully)
- clear = clearing the terminal window

## **Git Commands**

| Command     | Description |
| :---        |    :----:   |
| git init 'directory'      |  creating an empty git repository in a specified directory      | 
| git clone 'repo'  | cloning a repo located at 'repo' onto the local machine        | 
| git config user.name 'username'      |  defining the author name to be used for all commits in the current repo      | 
| git config --global user.name 'username'      |  defining the author name for all commits by the user      | 
| git add 'directory'  | staging all changes in 'directory' for the next commit        | 
| git commit -m "message"  | committing the staged snapshot, using "message" as the commit message  | 
| git status | listing files that are staged, unstaged, and untracked        | 
| git log      |  displaying the entire commit history using the default format     | 
| git log --oneline     |  displaying a summary of the commit history in a single line     | 
| git diff | showing the unchanged changes between your index and the working directory        |
| git reset | resetting the staging area to reflect the most recent commit, while leaving the working directory unchanged      |
| git reset --hard | resetting the staging area and the working directory to reflect the most recent commit and overwriting all changes in the working directory     |
| git reset 'file'      |  removing 'file' from the staging area, while leaving the working directory unchanged    | 
| git branch | listing all of the branches in your repo      |
| git branch 'branch'| creating a new 'branch' in your repo      |
| git checkout -b 'branch' | creating and checking out a new branch called 'branch'     |
| git merge 'branch'      |  merging 'branch' into the current branch    | 
| git remote add 'name' 'url' | creating a new connection to the remote repo      |
| git fetch 'remote' 'branch' | fetching a specific branch from the repo      |
| git pull 'remote' | fetching a specified remote's copy of the current branch and merging it into the local copy     |
| git push 'remote' 'branch'      |  pushing the branch to 'remote'    | 
