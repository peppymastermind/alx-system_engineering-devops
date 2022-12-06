A script that creates an alias
echo hello $USER (script that prints hello user, where user is the current Linux user.)
PATH=$PATH:/action (Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.)
echo $PATH | tr ":" "\n" | wc -1 (script that counts the number of directories in the PATH)
printenv (script that lists environment variables.)
set | less (Create a script that lists all local variables and environment variables, and functions.)
BEST ="School" (Create a script that creates a new local variable)
export BEST="School" (Create a script that creates a new global variable.)
echo $((TRUEKNOWLEDGE+=128)) (cript that prints the result of the addition of 128 with the value stored in the environment)
