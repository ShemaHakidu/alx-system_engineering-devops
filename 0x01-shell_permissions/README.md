su <username>: switches the current user to the user you need
whoami: print effective username
groups <username> Prints groups the user is in
chown betty hello: changes ownership of file hello to betty
touch hello: creates empty file hello
chmod u+x hello: adds execute permission to the owner of the file hello
chmod u+x,g+x,o+r heello:  adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
chmod a+x: Execute permissions to all users
chmod 007 hello: Write a script that sets the permission to the file hello as follows:

Owner: no permission at all
Group: no permission at all
Other users: all the permissions
chmod 753  hello: sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
chmod --reference= olleh hello: sets the mode of the file hello the same as olleh’s mode.
chmod -R a+x */: adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
mkdir -m 751 my__dir: creates a directory called my_dir with permissions 751 in the working directory
chown :school hello: changes the group owner to school for the file hello
chown -R vincent:staff .: Write a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.
chown -h vincent:staff_hello:changes owner and group for symbolinc file _hello
chown --from=guillaume betty hello: that changes the owner of the file hello to betty only if it is owned by the user guillaume
telnet towel.blinkenlights.nl: Write a script that will play the StarWars IV episode in the terminal.
