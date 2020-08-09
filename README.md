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
          - Assembly  
          - CPP  
          - Haskel  
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

Authetication, Add User Email & Name
>_git config --global user.email "you@example.com"_

>_git config --global user.name "Your Name"_

Omit --global

Commits to local directory
> _git commit -m 'Add logs & stuff'_

Omit **--global** to set the identity only in this repository.
     ###
>**Example:** _git commit -m 'README.md changed'_  

Push code (or project) to local directory
>_git push_  

Pull code (or project) to Git server directory
>_git pull_  

Similar to _pull_ !!! (IDK Yet)
>_git fetch_  

**Clone a Entire Project**
>_git clone https://github.com/user-name/project-name.git_  

#### For more:
>_man git_  

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
- Give GitHub **User Name** & **Passward**  
- The project will be uploaded (commited) to GitHub  
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
#### Mard Down  
- https://www.markdowntutorial.com/  
- https://dillinger.io/    
- https://stackedit.io/app#  
#### Linux Assembly  
- x86_64 Linux Assembly #1 - "Hello, World!" - kupala
  - https://youtu.be/VQAKkuLL31g  

#### Stack Overflow (GitHub API v3)
-

### This project is for testing purpose only.

#### Project URL:
[**Hello World**](https://github.com/mh1011/hello-world)
