# Repository management and collaborative science platforms. GitHub and Gitlab.

*Objectives of this session:*

- To create a repository and include the basic information.
- To know in detail the version history of the repository.
- To manage and compare the versions of the files in the repository.
- To know what are fork and pull request on repositories.
- To manage different branches for a repository.
- To collaborate and to share with other members in a repository.
- To learn about other features to improve the work with repositories.

<!-- vscode-markdown-toc -->
* 1. [Session content](#Sessioncontent)
	* 1.1. [Creating a new repository and configure the main options](#Creatinganewrepositoryandconfigurethemainoptions)
	* 1.2. [Adding content to our repository](#Addingcontenttoourrepository)
	* 1.3. [Working with the version history](#Workingwiththeversionhistory)
	* 1.4. [Forking a repository and creating a Pull Requests](#ForkingarepositoryandcreatingaPullRequests)
	* 1.5. [Adding different branches to your repository](#Addingdifferentbranchestoyourrepository)
	* 1.6. [Collaborating with other users and reposositories](#Collaboratingwithotherusersandreposositories)
	* 1.7. [Other advanced features](#Otheradvancedfeatures)
* 2. [Exercises](#Exercises)
	* 2.1. [Exercise 1: Create an initial repository for this session.](#Exercise1:Createaninitialrepositoryforthissession.)
	* 2.2. [Exercise 2: Managing forks to collaborate.](#Exercise2:Managingforkstocollaborate.)
	* 2.3. [Exercise 3: Managing branches](#Exercise3:Managingbranches)
* 3. [Exercise 4: Collaborating with other repositories and users](#Exercise4:Collaboratingwithotherrepositoriesandusers)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Sessioncontent'></a>Session content

###  1.1. <a name='Creatinganewrepositoryandconfigurethemainoptions'></a>Creating a new repository and configure the main options

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

:warning: *To complete this tutosessionrial, [you need a GitHub account](http://github.com/) and Internet access. You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on). If you have a question about any of the expressions used in this session, head on over to the [glossary](https://docs.github.com/en/get-started/quickstart/github-glossary) to find out more about our terminology.*

A repository is usually used to organize a single project. 
Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a `README` file, a file with information about your project. `README` files are written in the plain text [Markdown language](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). You can use this cheat sheet to get started with Markdown syntax. GitHub lets you add a `README` file at the same time you create your new repository. GitHub also offers other common options such as a *license file*.

We want yo create reate a repository named `XXXX` where you can store ideas, resources, or even share and discuss things with others. To do that:

- :one: In the upper-right corner of any page, use the drop-down menu, and select **New repository**. ![practice example 1](./media/practice1.1.png)
- :two: In the Repository name box, enter XXXX. [practice example 1](./media/practice1.6.png)
- :three: In the Description box, write a short description. [practice example 1](./media/practice1.7.png)
- :four: Select Add a README file. Then we will change it. [practice example 1](./media/practice1.8.png)
- :five: Select whether your repository will be Public or Private. In or case we will select Public. [practice example 1](./media/practice1.9.png)
- :six: Click Create repository. [practice example 1](./media/practice1.10.png)

[practice example 1](./media/practice1.2.png) 







###  1.2. <a name='Addingcontenttoourrepository'></a>Adding content to our repository

###  1.3. <a name='Workingwiththeversionhistory'></a>Working with the version history

###  1.4. <a name='ForkingarepositoryandcreatingaPullRequests'></a>Forking a repository and creating a Pull Requests

###  1.5. <a name='Addingdifferentbranchestoyourrepository'></a>Adding different branches to your repository

Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to main.

When you create a branch off the main branch, you're making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The main branch
- A new branch called feature
- The journey that feature takes before it's merged into main

[practice example 1](./media/practice1.3.png) 

Have you saved different versions of a file? Something like:

    story.txt
    story-edit.txt
    story-edit-reviewed.txt

Branches accomplish similar goals in GitHub repositories.

In GitHub, use branches for **keeping bug fixes** and **feature work** separate from our main (production) branch. When a change is ready, you can merge branches  into main.

**To create a new branch**


- :one: Click the Code tab of your XXXXX repository. [practice example 1](./media/practice1.4.png) 
- :two: Click the drop down at the top of the file list that says main. Branch menu
- :three: Type a branch name, readme-edits, into the text box.[practice example 1](./media/practice1.5.png) 
- :four: Click Create branch: readme-edits from main.

Now you have two branches, `main` and `readme-edits`. Right now, they look exactly the same. Next you'll add changes to the new branch.


###  1.6. <a name='Collaboratingwithotherusersandreposositories'></a>Collaborating with other users and reposositories

###  1.7. <a name='Otheradvancedfeatures'></a>Other advanced features 

##  2. <a name='Exercises'></a>Exercises

###  2.1. <a name='Exercise1:Createaninitialrepositoryforthissession.'></a>Exercise 1: Create an initial repository for this session.

For this training exercise it will be necessary to create a new repository with the following initial configuration data

- Repository name: ``reproducibility-with-git``.
- Repository description: ``Repository for the execise 1.``.
- Repository scope: ``Public``.
- Licence: For example select the ``MIT licence``.
- Add a default ``README.md``.

In the following image you can see the options to select for the creation of the repository:

 ![exercise example 1](./media/exercise1.1.png)



###  2.2. <a name='Exercise2:Managingforkstocollaborate.'></a>Exercise 2: Managing forks to collaborate.

In this exercise we are going to use an existing repository to *Fork* and interact with it, and finally propose some changes to be merged with the original existing repository by using a *Pull Request*

To do this, we first go to the existing repository we want to *Fork*:

To do this, we first go to the existing repository we want to fork:

https://github.com/manuparra/reprod-csic-exercise2

Then, from the top right menu click the "Fork" button and you will see a screen to select which organisation (of which you are a member) will do this operation, select one of them and in a few moments the repository will be a fork of the original one. If you are not a member of an organisation, it will directly Fork the repository.

You should see something like this, where the name of the repository is indicated and below it the original repository of the "Fork":

 ![exercise example 1](./media/exercise2.1.png)


Now you have to make the following change:

- Use the `Add` option to include a folder with your name and inside that folder a `Readme.md` file with the following text:

> \# Course of Reproduciblity @CSIC
> In this course I will learn:
> Control version platforms, containers and more !.

`Commit` the change and add a short description of this change like `Updated folder and readme.md`.

Now it is time to contribute the changes made by making a Pull Requests, i.e. requesting the original repository that we "would like" to include these changes in the original repository. To do this go to the main repository screen and select the following option:

 ![exercise example 1](./media/exercise2.2.png)


Doing this checks that there are no conflicts and you can propose the change by including a comment about the changes you want to bring to the original repository. 

![exercise example 1](./media/exercise2.3.png)

Include a title and a short description and then click `Create pull request`:

![exercise example 1](./media/exercise2.4.png)

Once this is done, you will have to wait for the original repository owner to review the request and accept it. When this happens you will be notified shortly :smile:.

###  2.3. <a name='Exercise3:Managingbranches'></a>Exercise 3: Managing branches

Branches allow you to develop features, fix bugs, or experiment with new ideas in a contained area of your repository isolated from the original repository.

In this exercise, two branches will be created, one for development and one for testing. Let's say that the development branch will be the one that will include the new features and the test branch will be exclusively for testing new things.

We go back to our repository created in exercise 1. From there we create two branches. To do this, create a new branch from the next option on the main screen of your repository and name it "development". 

![exercise example 3](./media/exercise3.1.png)

Again we do the same and create another new branch called "test". 

![exercise example 3](./media/exercise3.2.png)

You will see that when you select this icon, all the available branches will appear and you can switch between them to make changes in each one.

![exercise example 3](./media/exercise3.3.png)

Now we are going to switch to the development branch and modify the README.md file, adding the following lines to the end of it:

> \# Session 1: Exercises.
> \- Created a new branch for development.

Once this is done, we are going to merge the changes from the development branch with the main branch. To do this, click on view branches and then on view all branches:

![exercise example 3](./media/exercise3.4.png)


From here we can merge the changes made in the development branch with the main branch. Click on the `New pull request` button to do this. 

![exercise example 3](./media/exercise3.5.png)

 Once this is done, check that the merged changes already appear in the main branch by default.

##  3. <a name='Exercise4:Collaboratingwithotherrepositoriesandusers'></a>Exercise 4: Collaborating with other repositories and users

For this exercise you need to use the following document where each of the repositories from exercise 1 are listed for each user. 

- Select a user from the list and access their repository.
- Once on the website of the selected repository, go to the `Issues` option and `Add` to the user an action or correction to do on their repository, for example:

![exercise example 4](./media/exercise4.1.png)

> Hi, I have reviewed your repository on reproducibility and I think you should add in the Readme.md file a link to another version control platform: GitLab. Here is the link https://gitlab.com. 


![exercise example 4.2](./media/exercise4.2.png)

:bulb: *Use the @ to type the name of the repository owner for more direct notification. For example: @manuparra*.