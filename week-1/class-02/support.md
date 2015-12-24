# Supporting Information
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
###Create a new GitHub Repository
If you have not already, create a new GitHub Repository called guessing-game on GitHub, and clone that repository to your local computer. Your cloned repository folder should be inside your class assignments folder (codefellows or projects or whatever).

Inside of the guessing-game directory on your computer, create an index.html file.

Make it look similar to the one we created in class today:
- Place your three guessing game questions in 'prompt's
- Store the user input into a separate variable for each question
- Console.log() the response to each question with a useful message, like we did in class
- In an a sequence of 'alert's to the user, give the user a message repeating the answers that they gave to the questions

##+++++Reminder: Add, Commit, Push (Git Workflow)+++++

###Respond to the user using if/else and 'alert'
Now let's give some feedback to the user about whether they gave the right or wrong answers to your questions. In your JS, immediately after each 'prompt', use a if/else statement to test whether the user gave the correct answer. If they gave the correct answer, display a specific and personalized confirmation message in an 'alert' (such as "Yay! You got it right, Chris! I was indeed born in South Dakota!"), and if they gave an incorrect answer, display a specific and personalized alternate message (such as "No, sorry Chris, I was born in Liechtenstein, not South Dakota."). Do this for each of the three questions.

###Add in error correction
What if your user enters 'Y' instead of 'yes'? Or 'y' or 'YES'? Does your game still work correctly? It shouldn't. We need to build in some error correction. In your 'if' statements, where you are testing the user response, you need to add in && cases to your condition, such that Y/y/YES/yes or N/n/NO/no are all accounted for.

###+++++

Strive for clear and readable code style with proper indentation, line termination, and descriptive variable names.

(If you want to extend this assignment, add a fourth question that takes a numeric input and then indicates to the user whether the answer is correct, too high, or too low. You'll want 'else if' to make this work, and another piece of code called 'parseInt' that addresses data types. This part is not necessary for today, though... we'll cover it tomorrow.)
