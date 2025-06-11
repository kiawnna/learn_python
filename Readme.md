# Instructions for Learning Python
This is a directory you'll use to practice Python.

Start with the Getting Started section below, then check out the Daily Flow and Other sections.

## Getting Started
This is a template repository. That means you can use it as a template for your own personal repository.

To get started:
1. Click the green "Use this template" button above.
2. Give your repository a name like: `learn_python-<your_name>`.
3. Click "Create repository from template".
4. Go to GitHub and find your newly created repository.
5. Clone the template repo to your computer using Git Bash or Terminal by pasting the command: `git clone <url_of_your_new_repo>`

# TODO about how to set up git, xcode command line tools, etc

## Daily Flow
1. Open the folder in PyCharm or Visual Studio Code.
2. Start with `Day1Notes.md` and follow the instructions.
3. When finished, move on to `Day1.py` and follow the instructions.
4. When you think you have the correct answers in `Day1Notes.md`, and you think your program runs correctly in `Day1.py`,
add your changes and make a commit.
5. Push your changes to a `NEW` branch called: `day1-homework`, *not* the main branch, and create a `pull-request` to the master branch.
    * `git checkoub -b day1-homework`
    * `git add -p` --> insert y/n to each change you want to keep
    * `git commit -m "my day1 homework"`
6. `DO NOT MERGE` the pull-request.
7. Let me know you have pushed. I will either:
    * `Approve` your changes, or 
    * `Request fixes` by adding comments to your `pull-request`. You can either make the changes I comment on **OR** we 
    can hop on a call and do it together if you have questions.
8. Once you have successfully completed the Notes and Homework, I'll approve the changes and have you merge them into master.

## Other
* Feel free to do more than one day of work, but before moving on to a new Day all the previous Day's work must first be
merged into master (meaning I approved it and you did everything correctly).
  
* It's a good idea to review the Notes files every day to remind yourself of the different concepts you are learning. Having
a strong foundation in these basics is key. As long as you have that, you'll be able to do the more complicated stuff later.
  
* You can create new files as well, for example `Day1Extra.py` to practice your skills more. Look at the tasks from the 
original file and see if you can make up your own similar tasks, then complete them.