evel 1 -> level 2

LEVEL GOAL:

The password for the next level is stored in a file called - located in the home directory

-POSIX standards(for in dept go to [POSIX Standards](https://en.wikipedia.org/wiki/POSIX))

-The reason why all the commands start with '-' is due to POSIX standards

-'-' is used as a delimiter character, which are characters used to seperate distinct data elements

-if you want to open a file named '-' using simple commands, it will not work.

- 1st method- you can use 'cat ./-' where ./ is current directory, it is a path shortcut referring to the current directory you are currently in. ./ tells the shell to look for a file named - in the current directory.
     
- 2nd method- you can use 'cat -- -' where -- is end of options, The first -- argument that is not an option-argument should be accepted as a delimiter indicating the end of options. Any following arguments should be treated as operands, even if they begin with the '-' character.

- This level has taught me the importance of quoting or prefixing tricky filenames.

For more understanding of these commands you can use "command --help" in the terminal which will show how to use a command deeply and efficiently.


