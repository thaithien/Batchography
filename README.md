# Batchography: The Art of Batch Files Programming

This repository contains the scripts/recipes and snippets from the Batchography book (http://amzn.to/1X3tQ4K)


# Table of Contents

## INTRODUCTION

What are Batch files?  
Who is this book for?  
How to best read this book?  
Conventions used in this book  
What does the book cover?  
More Batch files scripting material  
## CHAPTER 1 – BATCH FILES SCRIPTING LANGUAGE BASICS  
<pre>
Getting started  
CMD keyboard shortcuts and other tips  
Customizing the command prompt
Recalling commands with keyboard shortcuts
Creating commands aliases with the DOSKEY utility
Automatically running a script when the command prompt starts
Path completion shortcuts
Editing tips
Useful commands
COLOR
ASSOC/FTYPE
TYPE
CLIP
RUNAS
DIR/COPY/XCOPY/MOVE/RENAME/DEL
PUSHD/POPD/CD/CHDIR/MD/MKDIR
Using the WMIC tool
Using the REG command to work with the registry
Process management commands
Command echo
The “Errorlevel”
Command extensions
Breaking long commands into multiple lines
Executing multiple commands on the same line
Compound statements
Conditionally executing multiple commands on the same line
Comments
Comments at the beginning of the line
Comments at the end of the line
Multi-line comments
Escaping special symbols
Passing command line arguments
Using the SHIFT keyword
Command line arguments and FOR loop variables modifiers
Environment variables
Manipulating environment variables
Useful environment variables
Localizing the environment variables block
Delayed environment variables expansion
Two-level environment variables expansion
Using the SETX command
Labels
The EOF label
Function calls
Checking the existence of a label
Taking input from the user
Standard Input/Output redirection
Special files and devices
Using output redirection in Batch file scripts
Using input redirection in Batch file scripts
Mixing input and output redirection
Pipes
Chaining pipes
Arithmetic operations
Summary
</pre>
## CHAPTER 2 – BATCH FILES PROGRAMMING
<pre>
Conditional statements
Multiline commands
Checking the command line arguments
Extended syntax
Switch/Case syntax
Repetition control structures
The FOR keyword
Extended FOR keyword syntax
The FORFILES command
Nested FOR loops
Using the GOTO and IF
String operations
String substitution
Sub-string
String concatenation
String length
Using variable parameters with string operations
String sorting
Using the FINDSTR command
Basic data structures
Arrays
Multi-dimensional arrays
Associative arrays
Stacks
Sets
Summary
Test your skills
</pre>
## CHAPTER 3 – CODING CONVENTIONS, TESTING AND TROUBLESHOOTING TIPS
<pre>
Coding conventions
Variables naming conventions
Avoid environment variable collision
Labels naming conventions
Persisting changes beyond the ENDLOCAL call
Using compound statements
Using the exit code
Using the FOR loop variables
Using temporary files
Writing recursive functions
Parsing command line arguments
Batch files calling other Batch files
Building, testing and using a utility Batch file script library
Testing the library
Debugging and troubleshooting tips
ECHO is your friend
Making your script debug-ready
Dumping the values of the work and state variables
Other tips
Summary
</pre>
## CHAPTER 4 – BATCH FILES RECIPES
<pre>
Simple console text editor
Check if the script has administrative privilege
Looking for a specific privilege
Checking if system directories are writable
Using known commands that fail to run without elevated privileges
Stateful Batch file scripts
Resumable Batch files
Converting ordinals to characters
Convert a string from upper case to lower case and vice versa
Extracting embedded text files
Embedding and extracting binary files and executables
Embedding foreign scripts inside your Batch file script
Embedding Python code in your Batch file script
Embedding JScript code in your Batch file script
Embedding Perl code in your Batch file script
Embedding PowerShell code in your Batch file script
Embedding any other script in your Batch file
Getting files information
Getting file’s last modification time
Getting file’s attributes
Getting a file’s size
Triggering a command when files are modified in a directory
Get the version string of MS Windows
Creating a compressed archive containing all your version controlled source files
Parsing INI files
Interactive Batch file scripts
Simple menus
Dynamic menus
Time for fun – Let’s play hangman!
Step 1 – Reading a random word from the list file
Step 2 – Drawing the hangman stick figure
Step 3 – Prompt and reveal
Step 4 – Putting it all together
</pre>
CONCLUSION


