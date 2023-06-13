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
Task 10: echo $(($BREATH ** $LOVE)):Write a script that displays the result of BREATH to the power LOVE

BREATH and LOVE are environment variables
The script should display the result, followed by a new line
Task 11:echo "$((2#$BINARY))": Write a script that converts a number from base 2 to base 10.

The number in base 2 is stored in the environment variable BINARY
The script should display the number in base 10, followed by a new line
Task 12: echo {a..z}{a..z} | tr " " "\n" | greo -v "oo": Create a script that prints all possible combinations of two letters, except oo.

Letters are lower cases, from a to z
One combination per line
The output should be alpha ordered, starting with aa
Do not print oo
Your script file should contain maximum 64 characters
Task 13: printf "%.2f" $NUM |sort or printf "%.2f\n" "$NUM": Write a script that prints a number with two decimal places, followed by a new line.

The number will be stored in the environment variable NUM.
Task 14:echo "$((10#$DECIMAL))": Write a script that converts a number from base 10 to base 16.

The number in base 10 is stored in the environment variable DECIMAL
The script should display the number in base 16, followed by a new line
Task 15:
