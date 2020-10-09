# 0x03. Git

## Foundations - 0-Day ― 0-Day

by Guillaume, CTO at Holberton School

weight: 1

### For this project, students are expected to look at these concepts:

    Source code management
    Git and Github cheat sheet - Everything in less than 30 seconds
    The Framework

## Resources

### Read or watch:

    Resources to learn Git
    About READMEs
    How to write a Git commit message

### Resources for advanced tasks (Read only after finishing the mandatory tasks):

    Elaine Yeung (Cohort 2, SF)‘ s Guidelines for the Github rookie - .gitignore
    Learning branching
    Effective pull requests and other good practices for teams using Github

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
### General

    What is source code management
    What is Git
    What is GitHub
    What is the difference between Git and GitHub
    How to create a repository
    What is a README
    How to write good READMEs
    How to commit
    How to write helpful commit messages
    How to push code
    How to pull updates
    How to create a branch
    How to merge branches
    How to work as collaborators on a project
    Which files should and which files should not appear in your repo

## Requirements
### General

    A README.md file at the root of the holbertonschool-zero_day repo, containing a description of the repository
    A README.md file, at the root of the folder of this project (i.e. 0x03-git), describing what this project is about
    Do not use GitHub’s web UI, but the command line to perform the exercise (except for operations that can not possibly be done any other way than through the web UI). You won’t be able to perform many of the task requirements on the web UI, and you should start getting used to the command line for simple tasks because many complex tasks can only be done via the command line.
    Your answer files should only contain the command, and nothing else

## More Info
### Install git

#### If git is not already installed on your terminal:
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```
#### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:
```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin master
```

## Tasks

### 0. Repo-session

Create a new directory called 0x03-git in your holbertonschool-zero_day repo. Make sure you include a README.md in your directory.

#### Repo:

    GitHub repository: holbertonschool-zero_day


### 1. Coding fury road

For the moment we have an empty project directory containing only a README.md. It’s time to code!

    Create these directories at the root of your project: bash, c, js
    Create these empty files:
        c/c_is_fun.c
        js/main.js
        js/index.js
    Create a file bash/holberton with these two lines inside: #!/bin/bash and echo "Holberton"
    Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
    Add all these new files to git
    Commit your changes (message: “Starting to code today, so cool”) and push to the remote server

#### Repo:

    GitHub repository: holbertonschool-zero_day
    Directory: 0x03-git
    File: bash/holberton, bash/school, c/c_is_fun.c, js/main.js, js/index.js


### 2. Collaboration is the base of a company

#### A branch is like a copy of your project. It’s used mainly for:

    adding a feature in development
    collaborating on the same project with other developers
    not breaking your entire repository
    not upsetting your co-workers

The purpose of a branch is to isolate your work from the main code base of your project and/or from your co-workers’ work.

#### For this project, create a branch update_script and in this branch:

    Create an empty file named bash/98
    Update bash/holberton by replacing echo "Holberton" with echo "Holberton School"
    Update bash/school by replacing echo "School" with echo "The school is open!"
    Add and commit these changes (message: “My personal work”)
    Push this new branch Tips

Perfect! You did an amazing update in your project and it’s isolated correctly from the master branch.

#### Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:

    Change branch to master
    Update the file bash/holberton by replacing echo "Holberton" with echo "Holberton School is so cool!"
    Delete the directory js
    Commit your changes (message: “Hot fix”) and push to the origin

Ouf, hot fix is done!

#### Repo:

    GitHub repository: holbertonschool-zero_day
    Directory: 0x03-git
    File: bash/holberton, bash/school, bash/98


### 3. Collaboration: be up to date

Of course, you can also work on the same branch as your co-workers and it’s best if you keep up to date with their changes.

For this task – and only for this task – please update your file README.md in the master branch from Github.com. It’s the only time you are allowed to update and commit from Github interface.

#### After you have done that, in your terminal:

    Get all changes of the master branch locally (i.e. your README.md file will be updated)
    Create a new file up_to_date at the root of your directory and in it, write the git command line used
    Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

#### Repo:

    GitHub repository: holbertonschool-zero_day
    Directory: 0x03-git
    File: README.md, up_to_date
