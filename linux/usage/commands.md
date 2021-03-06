# Linux commands

Here are some fundamental and common Linux commands with example usage:

## Filesystem

### ls

Lists the content of the current directory (or one that is specified). Can be used with the `-l` flag to display additional information (permissions, owner, group, size, date and timestamp of last edit) about each file and directory in a list format. The `-a` flag allows you to view files beginning with `.` (i.e. dotfiles).

### cd

Changes the current directory to the one specified. Can use relative (i.e. `cd directoryA`) or absolute (i.e. `cd /home/pi/directoryA`) paths.

### pwd

Displays the name of the current working directory, i.e. `pwd` will output something like `/home/pi`.

### mkdir

Makes a new directory, e.g. `mkdir newDir` would create the directory `newDir` in the present working directory.

### rmdir

Remove empty directories, e.g. `rmdir oldDir` will remove the directory `oldDir` only if it is empty.

### rm

Removes the specified file (or recursively from a directory when used with `-r`). Be careful with this! Files deleted in this way are mostly gone for good!

### cp

Makes a copy of a file and places it at the specified location (essentially doing a 'copy-paste'), for example - `cp ~/fileA /home/otherUser/` would copy the file `fileA` from your home directory to that of the user `otherUser` (assuming you have permission to copy it there!). This command can either take `FILE FILE` (`cp fileA fileB`), `FILE DIR` (`cp fileA /directoryB/`) or `-r DIR DIR` (which recursively copies the contents of directories) as arguments.

### mv

Moves a file and places it at the specified location (so where `cp` performs a 'copy-paste', `mv` performs a 'cut-paste'). The usage is similar to `cp`, so `mv ~/fileA /home/otherUser/` would move the file `fileA` from your home directory to that of the user otherUser. This command can either take `FILE FILE` (`mv fileA fileB`), `FILE DIR` (`mv fileA /directoryB/`) or `DIR DIR` (`mv /directoryB /directoryC`) as arguments. This command is also useful as a method to rename files and directories after they've been created.

### touch

### cat

Lists the contents of file(s), e.g. `cat thisFile` will display the contents of `thisFile`. Can be used to list the contents of multiple files, i.e. `cat *.txt` will list the contents of all `.txt` files in the current directory.

### head & tail

### chmod

### chown

### ssh

### scp

### su

### dd

### df

### unzip

### tar

### pipes

### tree

### &

### wget

### curl

### man



## Search

### grep

### awk

### find

### whereis



## Networking

### nmap

### hostname

### ifconfig
