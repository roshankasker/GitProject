# **Bash and Git Commands**
## **Bash Commands**

- cd = goes to the home directory
- cd 'directory name' = goes to a specific directory
- cd .. = goes up a directory
- ls = list contents of the current directory
- ls -a = list contents of the current directory, plus hidden files
- pwd = print working directory
- mkdir 'directory name' = make a new directory
- touch 'file name' = create new file with specific name
- echo 'String' = print text to the console
- echo 'String' > myTextFile.txt = writes String to file specified
- nano 'file name' = opens nano to edit the file, can also use vim
- mv 'file' 'location' = move files and folders
- cat 'file name' = read a file
- rm 'file name' = remove a file
- rmdir 'directory name' = remove/ delete an empty directory
- rm -rf 'directory name' = removing/ deleting a directory that is not empty (-r = recursively and -f means forcefully)
- clear = clears the terminal window

## **Git Commands**

| Command     | Description |
| :---        |    :----:   |
| git init 'directory'      |  create empty git repository in specified directory      | 
| git clone 'repo'  | clone repo located at 'repo' onto local machine        | 
| git config user.name 'username'      |  define author name to be used for all commits in current repo      | 
| git config --global user.name 'username'      |  define author name for all commits by user      | 
| git add 'directory'  | stage all changes in 'directory' for next commit        | 
| git commit -m "message"  | committing staged snapshot, using "message" as commit message  | 
| git status | lists files that are staged, unstaged, and untracked        | 
| git log      |  display entire commit history using default format     | 
| git log --oneline     |  display summary of commit history in a single line     | 
| git diff | show unchanged changes between your index and working directory        |
| git reset | reset staging area to reflect most recent commit, while leaving working directory unchanged      |
| git reset --hard | reset staging area and working directory to reflect most recent commit and overwrites all changes in working directory     |
| git reset 'file'      |  remove 'file' from staging area, while leaving working directory unchanged    | 
| git branch | lists all branches in your repo      |
| git branch 'branch'| creates a new 'branch' in your repo      |
| git checkout -b 'branch' | create and checkout a new branch called 'branch'     |
| git merge 'branch'      |  merge 'branch' into current branch    | 
| git remote add 'name' 'url' | create new connection to remote repo      |
| git fetch 'remote' 'branch' | fetches a specific branch from the repo      |
| git pull 'remote' | fetches specified remote's copy of current branch and merges it into local copy     |
| git push 'remote' 'branch'      |  pushes branch to 'remote'    | 

