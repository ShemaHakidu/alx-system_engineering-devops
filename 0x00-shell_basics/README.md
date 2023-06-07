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

