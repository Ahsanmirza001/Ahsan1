# Brief introduction of GitHub and Terminal
What Is the Terminal?
The terminal is a text based way to interact with the files and programs on your computer.
# what is git.
Git is a free and open source distributed version control system. Git's purpose is to keep track of projects and files as they change over time with manipulations happening from different users. Git stores information about the project's progress on a repository
How Git works?
Once you have Git installed on your system, sign-up on GitHub and create your first remote repository.
## Configure Git
After Git is installed on your system, you need to configure Git so that it can understand who is pushing the code to the remote repository, as many people could be working on the project. The most important configurations are the username and the user’s email. This can be setup using following commands.
```
git config --global user.name "Ahsan"
git config --global user.email "ahsanclouds@gmail.com"
```
After this, Git on your system will use these credentials every time you push some code to the remote repository. You can view all Git configurations using the command below.
```
git config --list
```
Initializing Git Repository
Let’s make a sample folder with name git-test which is same as our repository name we created on GitHub. This will be your local repository. After doing that, open the terminal window from within that folder.
First of all, we need make this folder a Git repository. It will be done by executing the command below.
```
git init
```


## Basic Terminal commands.
1. git Status
2. git add
3. git commit
4. git push
 
```
git status
```
The `git status` command displays the state of the working directory and the staging area.The best way to determine if I have your code is to check the status of your git repo with git status
```

```
The git add is a command, which adds changes in the working directory to the staging area.
```
git add add index.html
```
```
git commit -m " write any massage"
```
```
git push
```
# Navigating with in terminal and manipulation.
1. pwd its stand for present working directory. its tell me where i'm right now.
2.ls
3.ls -a
4. cd its stand for change directory for example if we write cd desktop in terminal its actuaaly change the path its means i change directory in desktop.then if i tped pwd its show im in desktop.
```
pwd
```
```
ls
```
ls is list of file in directory, if i write ls in terminal its gonna pull out everything in that directory. if we write command ls its will give you alot of options.
```
man ls
```
man ls stand for manual list its will bring up a lot of documentation if we scroll down we have lot of option and how to get out of this you need to scroll all the way down you will see colen sign press q "for quit" one more thing if we inthe manual ls scrol all the way down press forword slash and type and words we wanna to search to scrol town just type foeword slash and return
```
ls -l

```
its will give me full numbers of bites for example k.b, m.b etc
```
cd
```
```
cd ..
```
# setting up a repository.
```
git clone or downlond " url massage copied"
```
1. mkdir
2. git init
3. git remote and origin
4. git push origin master
```
mkdir
```
mkdir stand for make new directory
```
git init
```
```
cat
```
its stand for concatenate its very useful when we dealing with large data.
```
less
```
```
git remote and origin
```
```
git push origin master
```
# additional useful terminal commands
# special folders
home directory when i typeied pwd it show ahsan its my home directory.



Inline-style: 
![alt text]("https://drive.google.com/file/d/1jbW8hzYxhprvW2Bgiabk-3QNZdH6GcV6/view?usp=sharing")


file:///Users/mohammadahsan/Desktop/Screen%20Shot%202020-02-23%20at%208.40.50%20PM.png















