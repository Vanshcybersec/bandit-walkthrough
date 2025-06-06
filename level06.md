Level5 -> Level6

LEVEL GOAL:

The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

    human-readable
    
    1033 bytes in size
    
    not executable

    What I've learned:

-If you want to find  human-readable files then you can use file *. If that files contains '.' or '-' then you can use file -- *.
    
-If you want to find the size of files then you can use du command. it shows how much disk space a file or directory is using. du means DISK USAGE. By default it shows output in kilobytes KBs. du -h size in human readable format. du -sh only summary of directory. du -ah includes files with folders.

-If you want to list all hidden files and directories and want to find out their contents in a long listing format then use ls -laR here l=long listing,a=all files also hidden ones and R= recursive includes all subdirectories and their contents.

 For more understanding of these commands you can use "command --help" in the terminal which will show how to use a command deeply and efficiently.
