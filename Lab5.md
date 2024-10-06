# Lab5
## standard output
- \">\" after a command to create and save the output in a file.
- \"cat\" displays the content of a text file.
- \">>\" appends output to and extising file(if it doesn't exist, create new file).
## standard input
- \"<\" input from a file.
- \"|\" feeds output of previous command to input of next command.
## expansion
- Special characters expand its meaning when given to shell commands.
- echo *: print the file location that is editing.
- echo ~: print the home file location.
## permissions
- Linux is a multi-user system.
- Files and directories have a permission assigned differently to owner/group/others.
- rwxrwxrwx: read, write, execute for each owner/group/others. 
- \"chmod\" changes permissions.
- \"777\": rwxrwxrwx
- \"755\": rwxr-xr-x
- \"700\": rwx------
- \"666\": rw-rw-rw
- \"644\": rw-r--r--
- \"600\": rw-------
### superuser
- has all system administation authority.
- \"sudo\" before the command if you are a superuser.
- \"exit\" to get out of a superuser session.
## text editors
command line
- vi, vim
- Emacs
- nano

graphical
- gedit
- kwrite
## shell script
- write and run a shell script.
- \"sh filename.sh\" to print shell script.
## tips
- backslash can be used to ignore line change in command, to enter a long command in multiple lines.
- \"history\" to see previous command history.
- \"wget\" to download files from the internet directly to your active directory.
- \"curl\" fetching, uploading, and managing data over the Internet.
- \"grep\" Global Regular Expression Print, searching text within files.
