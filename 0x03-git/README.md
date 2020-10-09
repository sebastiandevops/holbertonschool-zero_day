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
