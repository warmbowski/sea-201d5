# Supporting Information

### Start today's work on a new Branch:

We reviewed how to create and work from a branch during lecture today, so you'll start today by creating a new branch called wednesday for your work. To create a branch, starting from Master:

`git checkout -b wednesday`

This will create a new branch (-b) and move to your new branch (checkout) at the same time.

### We'll be doing a lot of add-commit-push today (a-c-p)

    git add .     (Don't forget 'git status' to check your current state)
    git commit -m "some kind of meaningful message about the code you are committing"
    git push origin wednesday   (REMEMBER: Do not push directly to Master)

Always think of writing code in a series of steps, making sure that everything works in one step before moving to the next one. After each step, add-commit-push your work with a brief but descriptive commit message. This gives you a preserved backlog of your work with a descriptive history. This is useful for looking back at your code to see where problems emerged. We will review your commit history and your commit messages, so be sure to be attentive to this step.

# Git
#### Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

### Git Commands:
    git status              Provides a detailed description of current state in working directory

    git checkout -- <file>  Remove all changes to file to the point of the last commit.

    git add <file>          Include file in staged/tracked status of working directory

    git reset HEAD <file>   Remove file from staged/tracked status of working directory

    git commit -m ''        Snapshot the tracked changes in current working directory; with message

    git push                Push local commits to GitHub



## +++Add, Commit, Push+++
## +++Add, Commit, Push+++
## +++Add, Commit, Push+++


### Update your README file

Every repo needs a good README file. There's a lot of debate about what goes into a good README (take a look at http://stackoverflow.com/questions/2304863/how-to-write-a-good-readme), but at the least, you should have your name, the name of the project/assignment, a brief description of it, and citations to any code or sources you utilized in creating the code.

When you've got a good README finished, add-commit-push your repo to GitHub. Remember... the TA's will be checking for these intermediate commits when evaluating your assignment!
