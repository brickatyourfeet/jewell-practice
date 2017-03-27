#### [⇐ Previous](bonus.md) | [STRETCH: git and Github ⇒](git.md)

## STRETCH: Unix Commands

**Duration:** About 1.5 Hours

Read this article to familiarize yourself with the terminal: [How to Use Terminal: The Basics](http://mac.appstorm.net/how-to/utilities-how-to/how-to-use-terminal-the-basics/).

### Commands

Every developer will perform certain tasks--navigating a file system, viewing files of a directory, etc. The following commands will help you complete these tasks and are often faster than trying to do these same tasks in the Finder.

> To use Unix commands, you'll need to open a command-line interface, such as the [Terminal](https://en.wikipedia.org/wiki/Terminal_(OS_X)).

1. Navigating through a directory
  - `cd [argument]`
1. Print the current directory
  - `pwd`
1. Viewing files and directories
  - `ls [flag]`
1. Creating a file
  - `touch [filename]`
1. Copying a file
  - `cp [origin-path/origin-filename] [destination-path/destination-filename]`
1. Moving a file
  - `mv [origin-path/origin-filename] [destination-path/destination-filename]`
1. Creating a directory
  - `mkdir [directory]`
1. Open a file with the file reader
  - `less [filename]`
1. Reading a file
  - `cat [filename]`
1. Opening a file or directory
  - `open [filename or directory]`
1. Send the output of one command to a file
  - `[command] > [filename]`
1. Deleting a file
  - `rm [filename]`
1. Deleting a directory
  - `rm -rf [directory]`

---
##### Exercise:
1. Open up Terminal with Spotlight.
	* CMD+Space and type `terminal`

1. Go to your home directory by typing `cd`.

1. Print out the current directory and take note of what it is.

1. List out the folders in your home directory and locate the Desktop and Downloads folder.

1. Create a new folder called `galvanize`. Enter that newly created folder, and then create a new folder inside called `precourse`.

1. Go into the `precourse` folder and create a new file called `unix-commands.txt`.

1. Open Atom and navigate to this new `.txt` file. Type in your name on one line and your favorite color on the next line.
	* To open atom in the current directory from the terminal, type `atom .`

#### [⇐ Previous](bonus.md) | [STRETCH: git and Github ⇒](git.md)
