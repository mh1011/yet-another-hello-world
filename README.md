# "Hello World" Program For GitHub

##### Purpose of this program is to get myself familiarize with Git and GitHub.

#### Objectives:  
01. Install Git on the System  
          - GNU/Linux  
          - MS Windows
02. Familiarized with basic commands
03. Write a **Hello World** program in known languages (or have intention to learn)    
          - C  
          - Python
          - Assembly (x86_64)  
          - CPP  
          - Haskell  
          - Java  
04. Commit the program
05. Add a **README.md** file
06. Edit **README.md** file according to **Mark Down** syntax

#### Lists of Familiarized Commands:

Check Status of working files
>_git status_  

Adds files to index
>_git add filename_  

Add all
>_git add ._

Authentication, Add User Email & Name
>_git config --global user.email "you@example.com"_

>_git config --global user.name "Your Name"_

More Options:
>_git config --list

Commits to local directory
> _git commit -m 'Add logs & stuff'_

Omit **--global** to set the identity only in this repository.
>**Example:** _git commit -m 'README.md changed'_  

Push code (or project) to local directory
>_git push_  

Pull code (or project) to Git server directory
>_git pull_  

Similar to _pull_ !!! (IDK Yet)
>_git fetch_  

**Clone a Entire Project**
>_git clone https://github.com/user-name/project-name.git_  

#### .gitignore File
The .gitignore file ignore File(s), Folder(s) and stated Extensions from Commit.  

Add a **.gitignore** file
>_git .gitignore_

Edit the file and specify the items you want to ignore from commit.  

**Exclude specific extensions**  
>**Example:** _*.exe_  (Exclude .exe extensions)  

**Exclude specific file**  
>**Example:** _/filename.txt_  

**Exclude specific folder**  
>**Example:** _/Folder Name_  

#### git Help  
Opens in Web Browser in Git Bash (MS Windows)  
Opens in Terminal in GNU/Linux  
>_git **<verb>** --help_  
**Example:** _git config --help_  

>_git help <verb>_  
**Example:** _git help config_  

### Current Procedure (Console):  

#### Repository is created on GitHub  
- First, create a repository on GitHub by + > New repository
- Go to project folder using **_cd_**  
- Initiate Git if it's not initiated by: **_git init_**
- Use _git status_ to check for changes   
- Add GitHub link:  
>_git remote add origin https://github.com/user-name/project-name.git_  
- Then sync (IDK Yet) Local source to GitHub:  
>_git push -u origin master_  
- Give GitHub **User Name** & **Password**  
- The project will be uploaded (committed) to GitHub  
- Then cycle through these comments:  
>_$ git add ._  
>_$ git commit -m 'String & stuff'_  
>_$ git push_  

#### Pushing Local Repository on GitHub (Console)  
## Using GitHub API v3

- Go to project folder using **_cd_**  
- Initiate Git if it's not initiated by: **_git init_**  
- Add a remote Repository to GitHub using GitHub API v3
>_curl -u 'USER' https://api.github.com/user/repos -d '{"name":"REPO","description":" Project Description"}'_  
- Replace USER with your username and REPO with your repository/application name!
>_git remote add origin git@github.com:USER/REPO.git_  
>_git push origin master_

## Resources:
#### Git & GitHub Tutorials  
- Git & GitHub Crash Course For Beginners - Traversy Media  
  - https://youtu.be/SWYqp7iY_Tc  
- Git Tutorial for Beginners: Command-Line Fundamentals - Corey Schafer  
  - https://youtu.be/HVsySz-h9r4  
- Git Tutorial: Fixing Common Mistakes and Undoing Bad Commits - Corey Schafer  
  - https://youtu.be/FdZecVxzJbk  
#### Markdown  
- https://www.markdowntutorial.com/  
- https://dillinger.io/    
- https://stackedit.io/app#  
#### Linux Assembly  
- x86_64 Linux Assembly #1 - "Hello, World!" - kupala
  - https://youtu.be/VQAKkuLL31g  

#### Stack Overflow (GitHub API v3)
-

#### For more on git:
**man-pages**  
>_man git_  

**Web Page**  
- https://git-scm.com/

**Book(s)**
- [**Pro Git - Scott Chacon; Ben Straub**](https://git-scm.com/book/en/v2)  

### This project is for personal testing purpose only.

#### Project URL:
[**Hello World**](https://github.com/mh1011/hello-world)
