======================================
EPAM Python Software Engineer Training
======================================

*************************
Lesson 2: Files in Python
*************************

.. meta::
    :keywords: file, open, sys, os, path
    :description: Learn Python utilities to work with files

.. contents::

.. sectnum::

Course
======

String types
------------
In python files are opened as simple as using a builtin `open` function.
Inside an `os` module there are many useful routines to work with files, in
particular, a `path` class which contains functions to operate on file paths.

A `sys` module contains useful attributes pointing to standard input/output file
objects, application arguments, imported modules, environment variables.

Tasks
=====

Hello World
-----------
Write a simple application that writes a string ``Hello world`` into a file
specified as a command-line argument.

Hello John
----------
Write a program that reads a user name from standard input and prints ``Hello
<name>`` input a standard output.

Pipe
----
Write a program that redirects its standard input into a standard output line by
line (like a shell pipe operator).

List directory
--------------
Write a program that lists all file names, their permissions, ownership, last
modified date in a specified directory (like an ``ls -l`` shell command).  If no
directory is specified as the first (and only) command-line argument than a
current directory shall be listed.  If more than one argument is passed or the
specified directory does not exist and application shall report to standard
error and return an error status code.

Statistics
----------
Write a program that prints some statistics about itself to standard output:
a path to executable, command line arguments, imported module names and
corresponding file paths, environment variables.

Seek
----
Write a program that updates a current date and time in a file's first line
(stored in the first 50 characters).  A file shall be specified as a first
argument.  Other file content than first 50 characters shall not be modified.

