Git is a Version Control System

git --version  :- Is a command to know the git version

git config --list :- Gives us a email registered and some other info

cd file_name :- It changes the directory

mkdir file_name :- It creates new diectory

touch file_name.type :- It creates a file

ls :-  it shows the list of item in directory 

cat file_name.type :-  to see content of file

git init :- Powers your folder to be managed by git , and initializes a new empty repository. It also creates a .
git folder that has all the relevant logic to manage versions of your project

git status :- Gives us the status..

git add <file> :- moves the file from working area to staging area.

git rm --cached <file> :- removes file from staging area to working area.

commit :-  it is a particular version of the project. It captures a snapshot of the project's staged changes and 
create a version out of it.

git commit :-  registers staging changes to a commit (shift+i  -> "Message" -> esc  -> :wq -> enter)

git log :-  lists down all the commits of the repository

git restore <file> :-  Removes the changes made in the working area.

git restore --staged <file> :- It removes all the files changes from the staging area to be commited to the working 
area.(For staging area)

 git diff :- It shows us the difference b/w two commits.
 
git commit -m " "

git remote

git remote add <nameOfRemote> <link of the Remote>

git remote rm <nameOf Remote>

git remote rename <oldName> <newName>

## Git Recommended Practices ##
  make changes
  git add
  git commit
  git pull
  git push