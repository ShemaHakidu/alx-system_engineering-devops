# 0x02-shell, I/O redirections and filters project
Task 1: 0-hello_world: Prints Hello World
Task 2:Confused smily face: echo 'Ôo"
Task 3:Heloo file : cat /etc/passwd
Task 4:Two files: cat /etc/passwd /etc/hosts
Task 5:Last lines: tail -n 10 /etc/passwd
Task 6:fIRST Lines: head n 10 /etc/passwd
Task 7:third line: head -n 3 iacta | tail -n 1
Task 8:7-file:echo "Best School" > \*\\'"Best School"\'\\*$\?\*\*\*\*\*:)
Task 9:8 ls -la > ls_cwd_content:Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
Task 10: tail -n 1 iacta >> iacta:duplicats the last line into iacta
Task 11: find . -type f -name "*.js" -delete: Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
Task 12: find .find . -type d -not -name "." | wc -l : Write a script that counts the number of directories and sub-directories in the current directory.

The current and parent directories should not be taken into account
Hidden directories should be counted
Task 13: ls -t1 | head -n 10: Create a script that displays the 10 newest files in the current directory.

Requirements:

One file per line
Sorted from the newest to the oldest
Task 14: sort | uniq -u: Create a script that takes a list of words as input and prints only words that appear exactly once.

Input format: One line, one word
Output format: One line, one word
Words should be sorted
Task 15:grep "root" /etc/passwd: Display lines containing the pattern “root” from the file /etc/passwd
Task 16:grep -c "bin" /etc/passwd: Display the number of lines that contain the pattern “bin” in the file /etc/passwd
Task 17: grep -A 3 "root" /etc/passwd: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
Taks 18:grep -v "bin" /etc/passwd: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
Task 19:grep -i "^[a-z]" /etc/ssh/sshd_config or grep "^[A-Za-z]":Display all lines of the file /etc/ssh/sshd_config starting with a letter.
Task 20: tr 'Ac' 'Ze' or tr "A" "Z" | tr "c" "e":Replace all characters A and c from input to Z and e respectively.
Task 21:tr -d "cC": Create a script that removes all letters c and C from input.
Task 22:rev: Write a script that reverse its input.
Task 23:cut -d ":" -f1,6 /etc/passwd | sort: Write a script that displays all users and their home directories, sorted by users.

Based on the the /etc/passwd file
Task 24: find . -empty |rev|cut -d "/" -f 1 |rev:Write a command that finds all empty files and directories in the current directory and all sub-directories.

Only the names of the files and directories should be displayed (not the entire path)
Hidden files should be listed
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep
Task 25: find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d "." -f 2- | rev | LC_ALL=C sort -f: Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

Hidden files should be listed
Only regular files (not directories) should be listed
The names of the files should be displayed without their extensions
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line
The listing should end with a new line
You are not allowed to use basename, grep, egrep, fgrep or rgrep

Task 26:cut -c 1 | paste -s -d '':Create a script that decodes acrostics that use the first letter of each line.

The ‘decoded’ message has to end with a new line
You are not allowed to use grep, egrep, fgrep or rgrep
Task 27: cut -f 1 | sort |unique -c | sort -nr | head -n 11:Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

Order by number of requests, most active host or IP at the top
You are not allowed to use grep, egrep, fgrep or rgrep

