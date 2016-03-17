# Text Twist

Simple Text Twist game developed in the Webb Applications Security course (CPEG 470) / Spring 2016 / University of Delaware

A random rack and its possible words are retrieved from a back-end PHP file using AJAX. The dictionary is stored in a SQLite database.

## How to run

Must have a web server running (e.g. Apache) and SQLite installed.  
Put all the files in a folder accessible via HTTP (e.g. www or htdocs).

## How to play

The game is pretty simple.  
To Start, click on "Start" and wait.  
Now it's time to guess the words. Click on each letter and hit "Check".  
If the word is in the dictionary, the count label will decrease until the player guesses all words.