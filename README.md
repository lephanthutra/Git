# Git
Notes for using git

# Workflow in Git

- Firstly, create 2 braches including master branch and develop branch concurrently.

- Master Brach: Do not modify and do anything in this branch.

- Develop Branch: Where you can develop new features. From Develop Branch, you can create other branches to update code for each features.

Ex: Develop Brach (client request new task) => Future Branch (Developer conduct the given task => to develop new features => push code back to Develop Branch) => Develop Branch (Check and push code new Release Branch) => Release Branch (push code to Master Branch) => Master branch (merge and push code to Production) => Production (have any problem => request to Hot Fix Branch) => Hot fix branch

# Create virtual environment

Step 1: `py -m pip install --user virtualenv`

Step 2: `py -m venv env`

Step 3: `.\env\Scripts\activate`

# Create requirements.txt
=> Can use pipreqs to get the requirement.txt 

Step 1: `pip instal pipreqs`

Step 2: `pipreqs /path/to/project`

Step 3: `pip install -r requirements.txt`
