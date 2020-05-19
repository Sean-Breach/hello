# Hello World [![Sean-Breach](https://circleci.com/gh/Sean-Breach/hello.svg?style=svg)](https://circleci.com/gh/Sean-Breach/hello)

## Project Summary
This is a Hello World Demo to Test Continuous Integration with [Circle CI](https://circleci.com/)

## Setting Up Environment

1) Clone / Download Repo to your local environment `git clone git@github.com:Sean-Breach/hello.git`
2) Perform `make install` to install the required libraries
3) Perform `make lint` to validate project
4) Add / Commit / Push to your Git Hub Repo
    ```
    git add *
    git commit -m "feat: Code to Test CircleCI"
    git push
    ```
5) Go to [Circle CI](https://circleci.com/)
  * Connect your [Git Hub](https://github.com) Account
  * Select the _hello_ project and **Set Up Project**
  
## Repo File Documentation

* **.circleci** - Folder for the CircleCI **config.yml** for Continuously Integratation with Each Build
* **.gitignore** - Tells Git to Ignore Specific Files/Folders for Python
* **Makefile** - A series of directives for Build Automation of the Python Application
  * Install/Upgrade PIP
  * Perform Lint on hello.py
* **README.md** - Your Helpful Guide to this Crazy Project's Purpose
* **hello.py** - Simple Python Application that Returns '1'
* **requirements.txt** - List of Libraries to Install (We're Only Installing [Pylint](https://www.pylint.org/))
