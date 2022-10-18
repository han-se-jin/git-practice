# **Lecture 5(Shell Commands)**

### ***Standard Output***
screen
- **">"**
create and save the output in a file
- **">>"**
out put to an extising file(if it already exitsts)
create and write to a new file(if it doesn't exist)

### ***Standard Input***
keyboard
- **"<"**
input from a file

### ***Pipelines("|")***
feed output previous command to input of next command

### ***Expansion***
special characters expand its meaning 
- echo
 print it out as it gets
- echo*
 every file names 
- echo -
user's home directory

### ***TIP***
- **Backslash**
ignore line change in command
- **History**
see previous command history
save it to a text file

### ***Permissions***
- **-/rwx/rwx/rwx**
file type/owner/group/others
- **changing permissions**
chmod
![images](https://linuxcommand.org/images/file_permissions.png)
> rwx rwx rwx = 111 111 111
> rw- rw- rw- = 110 110 110
> rwx --- --- = 111 000 000
> rwx = 111 in binary = 7
> rw- = 110 in binary = 6
> r-x = 101 in binary = 5
> r-- = 100 in binary = 4

### ***Superuser***
system administation

### ***Text Editors***
> vi, vim
> Emacs
> nano
> gedit
> kwrite