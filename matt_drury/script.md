# Matt's Day One Lesson

## Introductions

  - Me, I'm Matt.
  - My history with Python.
  - Everyone introductions.
  - Objectives for this course.

## Setup a Computing Environment

  - `Slack`: This will be our main mode of communication outside of the classroom.  You need to install slack, then join the class slack channel and post a message.
  - Navigate to the class website: I'll post the link in the slack channel.
  - `Anaconda Python Distribution`: This is a very good way to get python, and all the libraries and plugins you need for this course.  Follow the [Installation Instructions](https://github.com/GalvanizeDataScience/python-fundamentals/tree/master/introduction) to get anaconda installed on your system.
  - `Text Editor`: You need a text editor for this course, *this is different than a document editor like microsoft word*.  If you do not already use a text editor, follow the [Installation Instructions](https://github.com/GalvanizeDataScience/python-fundamentals/tree/master/introduction) to get one.
  - `Git and Github`: We will be using these tools lightly to manage class materials.  Follow the [Installation Instructions](https://github.com/GalvanizeDataScience/python-fundamentals/tree/master/introduction) to get these installed.
  - `Command Line`: Programming is intimately tied to working in a command line (I'll explain what this means later).  If you're using Linux of Mac, you already have a command line.  If you're using windows, you can follow the [Installation Instructions](https://github.com/GalvanizeDataScience/python-fundamentals/tree/master/introduction) to install git-bash, which will give you the same experience.

## The Command Line

The dominant modern paradigm for interacting with a computer is a *Graphical User Interface*, which is very convenient for everyday users of computers.  Programmers prefer a different, more powerful, interface (though it will not be evident why at the outset), the *command line*.

  - Open the command line on your computer.
  - Understand the layout of a filesystem.
    - `pwd`: The current working directory.
    - Paths!
  - Use some commands to navigate the filesystem and manipulate files and directories.
    - `ls`: Listing files in the current working directory.
    - `cd`: Changing the working directory.
    - `mkdir`: Make a new directory.
    - `touch`: Make a new file.
    - `rm`: Remove a file.
    - `rmdir`: Remove a directory.


## Running Python from the Command Line

The easiest way to run python programs is from the command line.

  - Typing `python` will open the REPL (read-evaluate-print loop), a way to interactively work on python code.
  - Typing `ipython` will open a *better* REPL called `ipython`!
  - Let's write a simple python program in a text editor.

```
print("I'm gonna start counting now!")
for i in range(10):
    print(i)
print("I'm done counting now!")
```

Then save it as `first_program.py`.

  - We can run our program from the command line with `python first_program.py`.
  - Now let's do it in the REPL!


## Git and Github (If We Have Time)...

  - Fork the class repository to your own account.
  - `clone` your fork of the class repository.
  - Make a new repository on your account.
  - Clone your new repository.
  - Add a file to your new repository.
  - `add` and `commit` the new file.
  - `push` the new file to github.
