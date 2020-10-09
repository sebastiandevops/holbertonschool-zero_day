# 0x00. Vagrant

## Foundations - 0-Day ― 0-Day

by Julien Barbier, co-founder & CEO at Holberton School

weight: 1

#### For this project, students are expected to look at these concepts:

    Source code management
    Using Vagrant on the Holberton computers
    Git and Github cheat sheet - Everything in less than 30 seconds
    The Framework
    Using Vagrant on your personal computer

## Resources

### Read or watch:

    Zero day
    Virtual machine
    man uname
    Resources to learn Git
    About READMEs
    How to write a Git commit message

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
### General

    What is a zero-day
    What is a virtual machine
    What is Vagrant
    Who wrote Vagrant
    What is Ubuntu
    What does “Ubuntu” mean
    How to use VMs with Vagrant
    What does the command uname do
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

## Requirements
### General

    A README.md file at the root of the holbertonschool-zero_day repo, containing a description of the repository
    A README.md file, at the root of the folder of this project (i.e. 0x00-vagrant), describing what this project is about

## More Info
Install git

### If git is not already installed on your terminal:
```
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```
### Basic usage

At the end of this project you should be able to reproduce and understand these command lines:
```
$ git clone <repo>
$ touch test
$ git add test
$ git commit -m "Initial commit"
$ git push origin master
```


## Tasks

### 0. Create and setup your Git and Github account

Git is installed on the iMacs provided by Holberton, but if you’re using another computer, you might have to install it yourself.

    Configure your basic info (name, email) on your local machine – they will be part of your commits. Tips

#### On Github.com:

    Using the graphic interface on the website, create your first repository
        Name: holbertonschool-zero_day
        Description: I'm now a Holberton Student, this is my first repository as a full-stack engineer
        Public repo
        No README, .gitignore, or license

#### On your computer, open a terminal and do the following:

    Navigate to your home directory. Tips
    Create a directory holbertonschool-zero_day. Tips
    Navigate to this new directory. Tips
    Initialize git and add the remote origin
    Create a file README.md with Emacs (or other command line editors) and write a small Markdown text to present this project. This file is mandatory in all Holberton School projects
    Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin (Note: You will probably need to set your login/password to push to the remote server)

Good job!

You pushed your first file in your first repository of the first task of your first Holberton School project.

#### Repo:

    GitHub repository: holbertonschool-zero_day
    File: README.md


### 1. Hello Ubuntu

Inside the holbertonschool-zero_day repo, create a new directory called 0x00-vagrant. Add a README.md file to this directory.

ssh into your Ubuntu VM. What does the command uname print when you run it without any option?

Type your answer into a file in the 0x00-vagrant directory and push it to GitHub. Name your file accordingly as shown below.

#### Repo:

    GitHub repository: holbertonschool-zero_day
    Directory: 0x00-vagrant
    File: 0-hello_ubuntu
