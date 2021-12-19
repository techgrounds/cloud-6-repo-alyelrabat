# Bash scripting

Introduction:

The default command line interface in Linux is called a Bash shell. You’ve already interacted with Linux using commands in this shell.
A Bash script is a series of commands written in a text file. You can execute multiple commands in a row by just executing the script.
Additional logic can be applied with the use of variables, conditions, and loops among others.

In order to be able to execute the script, a user needs to have permissions to execute (x) the file.
Linux will only be able to find the script if you specify the path name, or if you add the path to the directory in which the script lives to the PATH variable.

Hint: although there are no file extensions in Linux, it’s easier for humans to understand if you end your script names with ‘.sh’.

## Exercise 1:

### Create a directory called ‘scripts’. Place all the scripts you make in this directory. Add the scripts directory to the PATH variable.

<img width="640" alt="BASHmkdir" src="https://user-images.githubusercontent.com/89514322/146691367-d83279d3-932a-4c64-9f9b-9f5857caaad5.png">

<img width="645" alt="export PATH=$PATH:$HOME:techgrounds:scripts" src="https://user-images.githubusercontent.com/89514322/146691326-afef650d-edd5-43e2-a2cc-cb5b478cf955.png">

### Create a script that appends a line of text to a text file whenever it is executed.


### Create a script that installs the httpd package, activates httpd, and enables httpd. 


### Finally, your script should print the status of httpd in the terminal.


## Variables:

You can assign a value to a string of characters so that the value can be read somewhere else in the script.
Assigning a variable is done using ‘=’.
Reading the value of a variable is done using ‘$<insert variable name here>’.

## Exercise 2:  

Create a script that generates a random number between 1 and 10, stores it in a variable, and then appends the number to a text file.
Conditions:
You can choose to only run parts of your script if a certain condition is met. For example, only read a file if the file exists, or only write to a log if the health check returns an error. This can be done using conditions.

A check for a condition can be done using ‘if’, ‘elif’, and/or ‘else’.
  
## Exercise 3:
  
Create a script that generates a random number between 1 and 10, stores it in a variable, and then appends the number to a text file only if the number is bigger than 5. If the number is 5 or smaller, it should append a line of text to that same text file instead.
