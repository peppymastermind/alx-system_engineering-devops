 0-hello_world script that prints Hello, World
1-confused_smiley script that displays a confused smiley
2-hellofile Display the content of the /etc/passwd file.
4-lastlines display the last ten lines of a file
5-firstlines display first 10 lines of a file
6-third_line display the third line of a file
8-cwd_state write a script into a file
9-duplicate_last_line duplicate the last line
find . -type f -name "*.js" -delete  -  script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -type d -not -name '.' | wc -l (script that counts the number of directories and sub-directories in the current directory.)
ls -t1 | head -n 10 (Create a script that displays the 10 newest files in the current directory.)
sort | uniq -u (a script that takes a list of words as input and prints only words that appear exactly once)
grep -i "root" /etc/passwd (Display lines containing the pattern root from the file /etc/passwd)
grep -c -i "bin" /etc/passwd (Display the number of lines that contain the pattern bin in the file /etc/passwd)
grep -i "root" -A 3 /etc/passwd (Display lines containing the pattern root and 3 lines after them in the file /etc/passwd.)
grep -i -v "bin" /etc/passwd (Display all the lines in the file /etc/passwd that do not contain the pattern bin)
grep -i "^[a-z]" /etc/ssh/sshd_config (Display all lines of the file /etc/ssh/sshd_config starting with a letter.)
tr "A" "Z" | tr "c" "e" (Replace all characters A and c from input to Z and e respectively.)
tr -d "cC" (Create a script that removes all letters c and C from input.)
rev (Write a script that reverse its input.)
cut -d ':' -f 1,6 /etc/passwd | sort (Write a script that displays all users and their home directories, sorted by user)
echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)(It is a good file that cuts iron without making a noise)
find . -empty | rev | cut -d '/' -f 1 | rev (Write a command that finds all empty files and directories in the current directory and all sub-directories.)
find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f (Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories)
cut -c 1 | paste -s -d ''(Acrostic)
l -n +2 | cut -f -1 | sort -k 1 | uniq -c | sort -rnk 1 | head -n 11 | rev | cut -d ' ' -f -1 | rev (Write a script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.) 
