A script that creates an alias
echo hello $USER (script that prints hello user, where user is the current Linux user.)
PATH=$PATH:/action (Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.)
ech $PATH | tr ":" "\n" | wc -1 (script that counts the number of directories in the PATH)
