The Command Line:

- a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.
- How to get to one:
  _ If you're on a Mac then you'll find the program Terminal under Applications -> Utilities. An easy way to get to it is the key combination 'command + space' which will bring up Spotlight, then start typing Terminal and it will soon show up.
  _ If on Linux then you will probably find it in Applications -> System or Applications -> Utilities. Alternatively you may be able to 'right-click' on the desktop and there may be an option 'Open in terminal'. \* If you are on Windows and intend to remotely log into another machine then you will need an SSH client. A rather good one is Putty (free) .
  Basic Navigation:
- PWD = print working directory. This tells you what your current or present working directory is.
- LS = short for list will help tell us what is in that directory
- A path is a means to get to a particular file or directory on the system.
- There are 2 different types of paths: 
  _ Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / )
  _ Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash. \* Change Directories - ie. move to another directory
  More About Files:
- Everything in the Linux system is a file including your keyboard and monitor
- Linux is an extentionless system using what is actually in the file to determine the type of file it is
- File naming is case sensitive where as other systems is case insensitive
- Spacing in file names is also ok
- Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden.
  Manual Pages:
- The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept.
- To invoke the manual pages use this command: man <command to look up>
- To perform a keyword search use this command: man -k <search term>
- To perform a each for ‘term’ use this command: /<term>
- When teaching within a manual page, select the next found item using: n
- The man pages are your friend.Instead of trying to remember everything, instead remember you can easily look stuff up in the man pages.
  File Manipulation:
- Linux file system is organized in a hierarchical way. Directories are easy way to organize/group files within your system
- To create a directory use this command: mkdir [options] <Directory Name>
- To remove a directory use this command: mdir [options] <Directory>
- To make a blank file use this command: touch [options] <filename>
- To copy/duplicate a directory use this command: cp [options] <source> <destination>
- To move a directory to a new location use this command: mv [options] <source> <destination> (this can also be used to rename a file or directory. Simply use the same/current location as the destination.)
- To delete a file/directory we use this command: rm [options] <file>
- No undo-The Linux command line does not have an undo feature. Perform destructive actions carefully.
- Command line options- Most commands have many useful command line options. Make sure you skim the man page for new commands so you are familiar with what they can do and what is available.
  Cheat Sheet:
- Filter commands (head/tail/wc) I am curious as to which instances you would need to view these besides a way to see what is in the file w/o opening them
- find /home -mtime -1
  Find all files in the given directory (and subdirectories) which have been modified in the last 24 hours. I can see this being useful when moving through multiple files in a short pd of time
- All of the process management commands especially kill and fg to help keep track of what is all running in the background.
