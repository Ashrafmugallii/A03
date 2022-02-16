# A03

Ashraf Mugalli

Github/Git/Webstorm tutorial

IS-117 102

01/28/2022

#1. Github

First, you need an account : 

Sign up for Github here: https://github.com/ 

Once you have created your account you want to create a repository. 
Repositories store all the necessary components of a single project. 
 
To create a repository: 

1. In the upper-right corner of the GitHub webpage, use the drop-down menu that has the + sign, and select New repository.
2. In the Repository name box, enter the name of your repository.
3. In the Description box, write a description of the repository.
4. Check the box that says Add a README file.
5. Click Create repository.

#Creating a branch

Branching allows you to work on different versions of the same project. There is a default main branch, instead of directly making changes to the main branch, we can separately work on changes that can be discussed with the team or yourself before merging the new changes into the main branch.

To create a branch: 

1. On the main page of your repository, Click the drop-down at the top left of your repository that says Master or Main.
2. You should see your branches and a textbox that says switch branches/tags
3. Enter the name of the new branch
4. Click Create branch: branch name from main

#Committing changes 

Any saved changes to your project is called a commit. 
You may either commit changes using the command line, or you may use Webstorm’s built-in Version Control Tools. 

1. Open your readme.md file and make some edits
2. when you are done, scroll to the bottom and you will see a commit changes box
3. Briefly describe the changes you've made to your file.
4. Once you are done click commit changes, These changes are commited to the branch you just created


#Opening a pull request

Pull requests are for your team members to review your changes and make a decision before merging into the main branch. You may open a pull request as soon as you make your first commit. Since you have already created a new branch and made edits to it, You are ready to open a pull request.

To Open a pull request

1. Click the tab that says "Pull requests" On your repository page
2. Click on New pull request
3. Click on the branch you created to compare it to the original 
4. Review the changes made and determine wether or not you want to keep them
5. Click Create Pull request
6. Give the pull request a name and a description
7. finally click create pull request

From there, the team members you are working with, or yourself, can review your edits and leave some thoughts.

#Merging pull requests

Merging allows you to combine the changes you have made to the original main branch

1. Click on Merge pull request 
2. Confirm Merge
3. Delete the branch

Now all the new changes are part of the main branch.

#2 Git

Github is an interface for the commandline tool Git




#3 Webstorm

Webstorm is an Integrated Development Environment (IDE)
Webstorm provides built in version control tools

Create an HTML project on Webstorm 

1. Click on create new project
2. Click on empty project
3. Give your project a name, and you may also choose a location 
4. Click create you should see your project files apear to the left of the IDE
5. Right click on your project folder, it should have the name of your project
6. Go to New > HTML file
7. Give your HTML file a name, you may also pick the version of HTML you would like to use, In this case choose HTML5
8. Now you are ready to edit your first webpage
9. On the top right side of the IDE, you can see that there is a menu that allows you to view your webpage in various web browsers. 
10. Click on Chrome, FireFox, Safari, etc. this will display your webpage on the web.

Now that you have made your first HTML webpage, you are now ready to use the Version Control feature integrated in Webstorm

** NOTE : I am using Mac OS so this may be different for other operating systems **

1. On the top menu in Webstorm click the VCS menu
2. Go down to the option "Create Git Repository"
3. This will open the file explorer
4. click your project folder and click Open
5. The VCS option on the menu bar changes to "Git"
6. Notice the files in your Project's folder turned red, this is indicating that your files have not been commited.
7. Go to the Git drop down menu and click commit changes, the shortcut for this on Mac is Control + K. 
8. Now on the left side you may select all the files you need to commit by checking the box next to the ones you want to commit.
9. Now that you have chosen your files, Write a short description of the changes you have made. 
10. Click on Commit
11. Now the changes have been commited and you are ready to share the project to Github

Sharing the project to Github

1. In the Git menu in the Webstorm IDE, Scroll down and choose Github > share project on Github. You will have to sign into your Github account. 
2. A box will appear, You can enter a description of the repository, then click share. 

You have succesfully shared your project to Github using Git.



#Glossary

1. Branch - Branches allow you to make changes to a copy of the main branch without affecting the main branch itself.

3. Clone -  A clone of a repository is just a copy of the repository stored locally on your machine where you can make edits without being online. You may push your local repository to the remote one.


5. Commit - A commit is any saved changes made to a file or files. Commits allow you to keep track of who made commits and when. Commits contain brief messages describing the changes made.

6. Fetch - When using git locally, you may want to get the most recent changes from the remote repository. You may do so using Fetch. 

7. Git - Free opensource version control system. I 

8. Github -  GitHub is an interface built off Git.

9. Merge - Merging allows you to bring your changes into your main branch once you are ready 

10. Merge Conflict - Merge conflicts occur when hit cannot distinguish which changes to keep and which to discard 

11. Push - Pushing allows you to transfer your local changes to a remote repository. 

12. Pull - Pulling allows you to bring changes from a remote repository and update those changes in your local repository. 

13. Remote - Remote is a command that allows you to manage connections to other repositories. 

14. Repository - Repositories store all the necessary components of a single project. 



Source

https://docs.github.com/en/get-started/quickstart/hello-world 
https://git-scm.com/docs/gittutorial 


