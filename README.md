# Bash-String-Manipulation
I was interested in finding all the video files in a directory and converting them to the mkv container.
the converting program requires an in and out file. I wanted the filename to be the same minus the extension.
I also wanted the conversion to take place in the existing filename directory. After that they would have custom tags inserted.
....blah blah blah.... After some irratation with cobbling together variables of paths / filenames / extensions
in loops where the global variable will not work I decided to investigate bash "String Manipulation".
This test is a colorfull example of that in a form that would fill my current need.

a few characters added to the filename (String-Manipulation) and its much cleaner.

This file loops through your directory of choice and performs the String Manipulation printed to stdout.
No changes are made to your files.
