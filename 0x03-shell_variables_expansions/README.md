A script that creates an alias
echo hello $USER (script that prints hello user, where user is the current Linux user.)
PATH=$PATH:/action (Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.)
ls -l | grep ^d | wc -l (script that counts the number of directories in the PATH)
