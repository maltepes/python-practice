# Overview

**Why are we using github?**

GitHub is a website where people store and share projects and code. Cloning a project means making a copy of the project on your computer. This allows you to open the files, run the code, make changes, or explore the project on your own computer without affecting the original project on GitHub. 

**Git vs Github:**

Git is a command line tool that keeps track of changes you make to files in a project. It remembers what was changed and when, so you can review or undo changes if needed.

GitHub is a website that works with Git. It lets you store projects online and share them with others. 

Using Git with GitHub makes it easy to download projects to your computer, make changes, and keep your work organized while staying up to date with changes made by others.

# **How to use github!**

You need to access the files in this repo. In order to do that, you need to clone the repo. The whole repo will be available on your local computer once you clone it. Git will allow you to do this. 

## 1. Install Git
   
Most Macs already have Git installed. To check, open Terminal and run:

      git --version

If you see a version number, Git is installed.
If you do not see a version number, install Git with Homebrew:

      brew install git

If you do not have Homebrew, install it with:

      /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## 2. Open your terminal

## 3. Choose a folder for the project

Navigate to the folder where you want the repository to live. 
For example, to use your Documents folder: `cd ~/Documents`

Replace Documents with any folder path you prefer.

## 4. Clone this repository

Click the green "Code" button and copy the GitHub CLI.
Paste that into your terminal.

Example:
      
      gh repo clone maltepes/repo-name 

This creates a new folder named repo-name with the project files.
