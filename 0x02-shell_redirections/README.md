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
Taks 18:
