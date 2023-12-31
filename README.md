# 0x16. C - Simple Shell

Write a simple UNIX command interpreter.

![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/235/shell.jpeg)

## 0. Betty would be proud

Write a beautiful code that passes the Betty checks

## 1. Simple shell 0.1

Write a UNIX command line interpreter

	Display a prompt and wait for the user to type a command.
	A command line always ends with a new line.
	Display the prompt again each time a command has been executed.
	The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
	The command lines are made only of one word. No arguments will be passed to programs.
	If an executable cannot be found, print an error message and display the prompt again.
	Handle errors.
	You have to handle the “end of file” condition (Ctrl+D)

	You don’t have to:

	use the PATH
	implement built-ins
	handle special characters : ", ', `, \, *, &, #
	be able to move the cursor
	handle commands with arguments

## 2. Simple shell 0.2

Handle command lines with arguments

## 3. Simple shell 0.3

Handle the PATH
fork must not be called if the command doesn’t exist

## 4. Simple shell 0.4

Implement the exit built-in, that exits the shell

## 5. Simple shell 1.0

Implement the env built-in, that prints the current environment

## 6. Simple shell 0.1.1

Simple shell 0.1 +

Write your own getline function
Use a buffer to read many chars at once and call the least possible the read system call
You will need to use static variables
You are not allowed to use getline
You don’t have to:

be able to move the cursor

## 7. Simple shell 0.2.1

Simple shell 0.2 +

You are not allowed to use strtok

## 8. Simple shell 0.4.1

Simple shell 0.4 +

handle arguments for the built-in exit
Usage: exit status, where status is an integer used to exit the shell

## 9. setenv, unsetenv

Simple shell 1.0 +

Implement the setenv and unsetenv builtin commands

setenv
	Initialize a new environment variable, or modify an existing one
	Command syntax: setenv VARIABLE VALUE
	Should print something on stderr on failure

unsetenv
	Remove an environment variable
	Command syntax: unsetenv VARIABLE
	Should print something on stderr on failure

## 10. cd

Simple shell 1.0 +

Implement the builtin command cd:

	Changes the current directory of the process.
	Command syntax: cd [DIRECTORY]
	If no argument is given to cd the command must be interpreted like cd $HOME
	You have to handle the command cd -
	You have to update the environment variable PWD when you change directory
	man chdir, man getcwd

## Authors

Moise Konan
