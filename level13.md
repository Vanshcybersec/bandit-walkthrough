Level12  -> Level13

LEVEL GOAL:

The password for the next level is stored in the file data.txt, which is a hexdump of a file that has been repeatedly compressed.

GIVEN HINT:

For this level it may be useful to create a directory under /tmp in which you can work. Use mkdir with a hard to guess directory name. Or better, use the command “mktemp -d”. Then copy the datafile using cp, and rename it using mv (read the manpages!)

WHAT I'VE LEARNED:

 -If any file is compressed in the gzip format, then, firstly, we have to make sure that it's name consists `.gz` at the end which is useful for the `gunzip` command.
 Now, after changing it's name to have .gz at the end using `mv` (a command used to move or rename files) we need to use the `gunzip` command so that is decompressed.

 -If the file is compressed in bzip format, then, firstly, we have to make sure that it's name consists `.bz2` at the end which is useful for the `bunzip2` command. Now, after doing that we need to use the `bunzip2` command on the file with `.bz2` at the end to decompress it.

 -If the file is compressed in POSIX tar archive format, then, firstly, we have to make sure that it's name consists `.tar` at the end which is useful for the `tar` command. Now, after doing that we need to use the `tar` command with `-xvf`(`-x` means extract or pull files out the archive, `-v` means verbose meaning it shows you the output of the command in a more detailed way, `-f` command tells `tar` command what file to extract) on the file with `.tar` at the end to decompress it.

 - the command `&&` can be used between these commands. It is used in such a way that if the first command is executed porperly then only the second command will run.
