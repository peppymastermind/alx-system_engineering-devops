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
 
