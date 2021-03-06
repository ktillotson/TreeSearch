TreeSearch | 12-04-2014 | RC1

About
-----

CS 2336.001 Class Project | Group 11 | Michael Aldridge | Michael Burdick | Nicholas Orton | Kyle Tillotson

TreeSearch is designed to run in Java to build a tree from a plain
text file, display the tree, then print the tree using preorder,
inorder, and postorder methods of transversal.  It utilizes it's
own command line interface finished by the insane Michael Aldridge.

Running
-------
TreeSearch comes pre-built with it's own .jar containing everything
needed to run in a pre-existing Java environment.  Just run (insert file name here)
and a window will open.  The program can also be run from the
command line using the following command:



Where xxxxxxxx.txt is the file you wish to build a tree of.

Building for Windows
--------------------
To build your own version, you need to install Maven which can be
found at maven.apache.org.  You will also need to have the most recent
version of the Java SDK installed.  After unzipping the
installation you will need to set up the following user environment
variables:
Variable	|	Value
M2			%M2_HOME%\bin
M2_Home		|	(location of your unzipped maven files)

You will also have to prepend "%M2%" to the path system variable.
Once finished, you then navigate to the directory containing
pom.xml, which should be the TreeSearch folder, and run the following
command:
	mvn package
Maven will then build and create a target folder, containing two .jar
files.  The one starting with "uber" will be the one that you can then
run either through by double-clicking or through the command line.

Documentation
-------------

Class dependant documentation can be found in the included .doc file.
Further information can be found at:
	www.utdallas.edu/~mwa130030TreeSearch/

Git Access
----------

The most up-to-date version can be found on git at:
	github.com/UTD-SC2336-TreeSearch/TreeSearch

System-specific Notes
---------------------

Program was built in Debian, a Linux based operation system.  It is
machine portable due to the nature of Java.  You can build it yourself
on whichever machine can run Maven, but you are better off using the
included .jar file.  Trust me.

----------------------------------------
(License go here)

[![Build Status](https://travis-ci.org/UTD-CS2336-TreeSearch/TreeSearch.svg?branch=master)](https://travis-ci.org/UTD-CS2336-TreeSearch/TreeSearch)
