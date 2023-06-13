0x03. Shell, init files, variables and expansions, Script descriptions:

Task 0: ls="rm *":Create a script that creates an alias, Name: ls Value: rm *
Task 1: echo "Hello $USER": Create a script that prints hello user, where user is the current Linux user.
Task 2: export PATH=$PATH:/action :Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program
Task 3: echo $((`echo $PATH |grep -o ":/" |wc -l` +1)):Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
Task 4:printenv:Create a script that lists environment variables.
Task 5:set; Create a script that lists all local variables and environment variables, and functions.
Task 6:BEST="School": Create a script that creates a new local variable.

Name: BEST
Value: School
Task 7:export BEST="School"
Task 8:ECHO $((128 + $TRUEKNOWLEDGE)): Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
Task 9: echo $(($POWER / $DIVID)): Write a script that prints the result of POWER divided by DIVIDE, followed by a new line.

POWER and DIVIDE are environment variables
Task 10:
