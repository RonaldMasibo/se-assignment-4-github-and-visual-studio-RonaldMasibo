[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15517558&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.
Repositories on GitHub:
    GitHub is a website used by software developers/engineers for hosting website code and showcasing their best coding projects either individually or collaboratively in various programming languages.
    
    Primary Functions - Hosting of websites for online storage purposes.
        - Showcasing of code used by different people thus, allowing for collaboration.
        - It contains a cloud-based version control system that enables developers track changes in their code

    Features - It enables developers create repositories that enable storing, managing & tracking changes in code
        - It contains pull requests that enables collaborration among developers & code review.
        - It contains GitHub Pages that enables hosting of static websites

    GitHub supports collaborative software development through the features above; by enabling creation of GitHub repositories for storing code. By storing this code, other developers using other PCs located elsewhere can then view the same code & provide their views, hence enabling collaboration among developers. 

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.
Version Control with Git:
    GitHub repository is a storage space on GitHub that allows developers to store and track changes of code in a file that has been programmed using a programming language.

    Creating a new repository:
        - On the panel on the left, click the green icon that contains "New" on it to show that you're creating a new repository
        - On the corresponding page, give the repository a name of your choice.
        - You have the option of briefly describing your repository under "Description" as it's optional
        - There is also the optional choice of adding a "READ ME" file that enables you to broadly describe your project later on
        - Click on the "Create repository" command

    Essential Elements:
        - Name of repository
        - Description about your repository either through the "Description" box or by adding a "READ ME" file& describing it from there
        - An indication of whether the repository is "public" for anyone to be able to interact with its contents or "private" for specific developers to be able to interact with its contents
        - Pull requests to enable developers make changes to its contents through Git

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?
Branching and Merging in GitHub:
    Version control is the simultaneous coding of a programming project while kepping track of any changes that may occur and if need be, to revert to previous versoins.
    Since GitHub provides a platform for developers to collaborate on programming tasks together, version control is enhanced by using Git to keep track of change by multiple developers.

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.
Pull Requests and Code Reviews:
    Branches are a feature of GitHub that enables developers to tackle different tasks from the main coding file.
    Importace - Enables developers to express their ideas in coding without risk of losing initial or overall coding file
        - Branches allow developers to work on different tasks without affecting the main codebase
        - Branches make it easier to track development history of features, bug fixes & releases of coding projects
    Process of creating a branch:
        - Creating a new branch using the command below;
            git checkout -b <branch-name>
        - Making changes to the new branch ie adding,updating or deleting files and then staging all the changes using the commands below;
            git add.
        - Commiting the changes made with a message describing the changes made;
            git commit -m "Describe the changes made here"
        - Push the branch onto GitHub using the command below;
            git push -u origin <branch-name>
        - Switch back to the main branch;
            git checkout main
        - Merging the branch using the command below;
            git merge <branch-name>

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.
GitHub Actions:
    GitHub pull request is a feature that allows developers to review code of a repository before it's merged by allowing changes made to be merged into the 'main' branch of a repository.
    By pushing requests to GitHub, a developer is able to upload the changes made as "commits" to a remote repository. Pull requests enable developers to be able to download these changes from a remote repository to the local repository. This enhances code review & collaboration amongst them.

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.
Introduction to Visual Studio:
    GitHub Actions is a feature of GitHub that enables developers to automate undergoings in the repositories.
    How it's used to automate workflows:
        - Continous Integration (CI) - automatically building & running code
        - Continous Deployment (CD) - automatically deploys software applications after CI is successful.
        - Automated Code Reviews - automatically runs analysis on pull requests
        - Notification triggers - automatically sends a form of communication whenever certain activities occur.

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?
Integrating GitHub with Visual Studio:
    Visual Studio is an example of an Integrated Development Environment application that software engineers use to efficiently develop software code using programming languages.
    Key Features:
        - Suports a wide range of extensions like Dart, Flutter etc that enables developers customize it according to their needs
        - Contains its own terminal that enables developers to operate through it as well as the local computer machine the same way the local CLI does.
        - It's versitile as it supports programming using different programming languages like Python, Javasript, C++ etc
    Difference from Visual Studio Code:
        Visual Studio is designed for developers to tackle large-scale projects as it supprts a wide support of a variety of progarmming languages while Visual Studio code us designed for developers to tackle relatively small-scale projects.

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?
Debugging in Visual Studio:
    Steps:
        - Create a new repository in your GitHub account
        - Fork your repository on GitHub
        - Copy the code link of your GitHub repository
        - Assuming that Git Bash has been installed, make sure that the default terminal of your visual studio application is Git Bash
        - Clone the repository created on GitHub onto the terminal of visual studio using the command below:
            git clone <link of GitHub repository>
        - Make changes to the repository by either adding, updating or deleting a code file
        - On the terminal of Visual Studio, enter the command below to update the changes on GitHub:
            git add .
        - Still on the terminal, commit the changes made with a message description:
            git commit -m "Describe the changes made here"
        - Push the changes made onto GitHub on the terminal:
            git push
    This integration enhances workflow by enabling developers access GitHub using visual studio without necessarily having to directly access their GitHub accounts to make the changes of code files in the GitHub repositories.

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?
Collaborative Development using GitHub and Visual Studio:
    Debugging Tools:
        - Breakpoints - is a debugging tool that enables execution of code upto a specific line of code.
        - Live Unit Testing - is a debugging tool that enables automatic runnig of code files as code is written & edited.
        - Edit & Continue tool - is a debugging tool that enables updating or changing of code as debugging as well takes place with immediate application of the changes made without necessarily having to restart the debugging session.
    Developers can use debugging tools to make their programming work easier when coding e.g the Edit & Continue tool will help in saving time & effort of having to restart a debugging session when changes are made in code files. If a whole code file does not run as intended, the Breakpoint tool can be used to check upto what point does a section of code work, thus helping to locate where the main issue is.

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.
    As seen earlier, GitHub can be integrated with Visual Studio. With Push & Pull requests for version control, coding projects can be accessed by different developers on their respective local computer machines & thus, enabling them to collaborate and share their ideas together on how to tackle certain challenges in coding.
    Real-world example:
        Creating an e-commerce website and pushing it to GitHub for other developers to issue their ideas as to which changes could be made or updates to the code that could be made.


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
