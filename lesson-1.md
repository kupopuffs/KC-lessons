# What is Markdown (e.g. README.md)
* markdown is like HTML but cleaner
* markdown is how we write documents in easy and clean way
* used all over Github!
* it's good to practice writing different kinds of code too
### Symbols/Features
* hashtag \# is for headings
  * lots of hashtags \#\#\#\# is for h4
* start \* is for bullet points
* \` for code sections
### Questions about Markdown
* Why does the code contain a slash in front of \#?
  * to the computer, a \# means you're going to put a heading
  * we don't want a heading, we just want to show the \# for our notes
  * So, we add a \\ to the code to escape the character

# Opening the Terminal
* to open the Terminal in Mac, press `⌘ + Space` to open Spotlight Search
* Type `Terminal` and `Enter` to open it

# Terminal Basics
* the terminal is a way to use/nagivate your computer using only code/text

# Lesson 1 - Cloning your Project
* Your project is at https://github.com/KCCodes13/Emerges-SFU-KC-Portfolio-FINAL
* Open the terminal, go to a directory fit for your project
  * e.g. `cd  KC-lessons/lesson-1/`
* In terminal, clone your git project
  * `git clone https://github.com/KCCodes13/Emerges-SFU-KC-Portfolio-FINAL.git`
* Change your Terminal's directory to your project
  * `cd Emerges-SFU-KC-Portfolio-FINAL/`
* That downloads your project, now we can open it in Visual Studio Code and make changes

# Lesson 2 - Make changes and commit them
* Open your folder in VSC, make a change
* In Terminal, type `git status` to see your changes
  * `git diff` to see the changes in Terminal
* If you like your change, type `git add <file>` to add it to your next commit
* `git commit -m "<message about your changes>` to commit your changes
  * you can see the change when you do `git log`
* `git push origin main` to push your change online

# Terminal commands
* `cd` change directory to your home
* `cd <directory>` change directory to `<directory>`
* `ls` list directory
* `pwd` list the present working directory (folder you're currently in)
* `mkdir <name>` make a folder/directory with the name

# Terminal Shortcuts
* pressing `Tab` in Terminal will make it guess the rest of what you're typing
* pressing `Up Arrow` in Termianl will make it repeat a previous command
  * keep pressing `Up Arrow` to go deeper into your history

# Git commands
1. `git clone <url to project>` to copy your git repo to your folder
1. `git log` to list a log of your changes
1. `git status` to list your modified files (and other info)
1. `git diff` to show what your changed
    1. green is your current changes
    1. red is your overwritten changes
1. `git add <file>` to add your file
1. `git add .` to add all changed files
1. `git pull` to get the latest changes from Online

# Example flow to make change
In your Terminal,
1. `cd` to change to your home directory
1. `cd workspace` to change to your workspace directory
1. `git clone https://github.com/KCCodes13/Emerges-SFU-KC-Portfolio-FINAL.git`
1. `cd Emerges-SFU-KC-Portfolio-FINAL` to change your Terminal's directory
1. make changes in Visual Studio Code
1. `git add .` to add all changes
1. `git commit -m <some message>` to commit your changes to your history
1. `git push` to upload