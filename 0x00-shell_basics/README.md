pwd: prints the absolute path name of the current working directory
ls: Display the contents list of your current directory
cd: Changes directory to home directory when there is nothing immediately after cd
ls -l: Prints working directory files in long format
ls -la: Display current directory contents, including hidden files (starting with .). Use the long format.
ls -aln: See directory contents in long format, with numeric IDs for users and groups including any hidden files.
mkdir /tmp/my_first_directory/: Creates a directory named my first directory in tmp
mv /tmp/btty /tmp/my_first_directory/: moves the file betty to my first directory
rm /tmp/my_first_directory/betty: deletes the files betty
rm -r /tmp/my_first_directory: deletes this directory and all its files
cd -: Go to previous directory
ls -la . .. /boot: Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
file /tmp/iamafile:  prints the type of the file named iamafile. The file iamafile will be in the /tmp directory
ln -s /bin/ls __ls__:Create a symbolic link to /bin/ls, named __ls__ in current working directory
cp -un *.html ../: a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
mv [[:upper:]]* /tmp/u:  a script that moves all files beginning with an uppercase letter to the directory /tmp/u
rm *~: Delete all files that end with the character ~
mkdir -p welcome/to/school: a script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

