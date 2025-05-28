Level 0 -> Level 1

-SSH stands for secure shell. Its a command and a prompt used to securely connect to another computer over the network (usually remotely). You can access the remote system's terminal, run commands on it, transfer files using tools like scp or sftp, administer servers, work on hacking labs or CTFs and do port forwarding or tunelling.

Level 1 -> level 2

-POSIX standards

-The reason why all the commands start with '-' is due to POSIX standards

-'-' is used as a delimiter character, which are characters used to seperate distinct data elements

-cat or concatenate is used for viewing, combining and creating text files from terminal

-if you want to open a file named '-' using simple commands will not work.

- 1st method- you can use 'cat ./-' where ./ is current directory, it is a path shortcut referring to the current directory you are currently in. 
     
- 2nd method- you can use 'cat -- -' where -- is end of options, The first -- argument that is not an option-argument should be accepted as a delimiter indicating the end of options. Any following arguments should be treated as operands, even if they begin with the '-' character.

Level 2 -> Level 3

-If you want to open a file which has space between its characters then it might get tricky. So, to open it use double quotes "" or single quotes '' or backslash between its each characters to open, create or delete that file. Single quotes ignore any special characters. Double quotes ignores all except $, back quotes and baclslashes.

Level 3 -> Level 4

-To open a hidden file you first have to use ls -a simply using ls wont show the hidden file. -a is shortcut for -all, it shows all files including hidden files when used with ls. The file will be show in ". .. .filename" format where . is the current directory and .. is the parent directory.

-To create a hidden file you can use touch .filename. touch is used for creating an empty file. The '.' is used to make the file hidden. you can use echo to add content in a hidden file. 
