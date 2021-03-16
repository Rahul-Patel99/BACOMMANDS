# **GIT AND BASH COMMANDS**
### Bash
|Command|Example|Description|
|--------|--------|--------|
|pwd|pwd|Print current working directory|
|cd _or_ cd~|cd|Goes to home directory|
|cd <directory name>|cd Documents/|Change to specific directory|
|ls|ls|List the contents of current directory|
|ls -a|ls -a|List the contents of the current directory, including hiddden files|
|touch <filename>|touch myText.txt|Creates a file with a specific name|
|nano <filename>|nano myText.txt|Opens nano to edit the file|
|vim <filename>|vim myText.txt|Opens vim to edit the file|
|echo <String>|echo hello|Prints text to console|
|echo <String> > myTextFile.txt|echo "Hellow World" > myTextFile.txt|Writes the String to the file name specified|
|mkdir <directory name>|mkdir myNewFolder|Makes a new directory|
|cat <filename>|cat myText.txt|Show contents of file|
|mv <file> <location>|mv myText.txt myNewFolder/|Moves file and folders. First arguement is where you want to move. Second arguement is where you want to move the file to|
|rm <filename>|rm myText.txt|Delete file
|rmdir <directory name>|rm myNewFolder|Removes an empty directory|
|rm -rf <directory name>|rm -rf myNewFolder|Delete a directory that has contents in it. -r flag means recursively and -f means forcefully
|clear|clear|Clears the terminal window|

### Git
|Command|Example|Description|
|--------|--------|--------|
|git init|git init|Initialises current directory as a git repository|
|git status|gi status| Lists which files are stages,unstaged and untracked|
|git log|git log|Displays entire commit history|
|git clone <repo>|git clone <URL>|Clones a repository to your local machine|
|git config user.name "<name>"|git config user.name(RahulPatel)|Defines author name used for local machine|
|git config user.email"<email>"|git config user.email"rpatel@qa.com"|Deines authors email for local machine|
|git config --global user.name "<name>"|git config --global user.name(RahulPatel)|Defines author name used for all commits by current user|
|git config --global user.email"<email>"|git config --global user.email"rpatel@qa.com"|Deines authors email for  all commits by current user|
|git add <directory>|git add myText.txt|Stages all changes in myText.txt for next commit
|git commit -m "message"|git commit -m "RP:updated myText.txt file"|Commit the stage with a message
|git push <remote> <branch>|git push origin master|Push the master branch to the origin|
|git pull <remote> <branch>|git pull origin master|Fetch the specified remote's copy of current branch and merges it into the local copy|
|git remote add <name> <url>|git remote add origin URL|Creates a new connection to a remote repository|
|git restore --stage <filename>|git restore --stage myText.txt|Restores the file from stage area|
|git remote --v|git remote --v|Shows where you fetch and push
|git branch|git branch|Shows existing branches|
|git branch -a|git branch -a|Shows all branches in remote that exist|
|git checkout <branchname>|git checkout main|Changes current branch to branch specified|
|git remote add upstream <URL>|git remote add upstream URL|Changers where you push and pull files|
|git fetch upstream|git fetch upstream|Pull changes from orginal repository to yours|
|git merge upstream/main|git merge upstream/main|Merges upstream/main into local origin/main|
|git diff|git diff|Shows differences between branches|
|git merge --abort|git merge --abort|Aborts a merge|
|git revert|git revert|Creates a new commit that does the opposite of the previous commit|
|git reset --hard <id>|git reset --hard 34rfh4|Returns state to selected commit|



