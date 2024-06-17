echo "Hello, World" - prints hello world to the 0-hello_world file
echo \"\(Ôo\)\' - a script that displays a confused smiley "(Ôo)'
cat /etc/passwd - Display the content of the /etc/passwd file.
cat /etc/passwd /etc/hosts - prints the content of /etc/passwd and /etc/hosts

tail /etc/passwd - Display the last 10 lines of /etc/passwd
head /etc/passwd - Display the first 10 lines of /etc/passwd
head -n 3 iacta | tail -n 1 - Write a script that displays the third line of the file iacta.
echo "Holberton School" | cat > '\*\\'\''"Holberton School"\'\''\\*$\?\*\*\*\*\*:)' - Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line
ls -la > ls_cwd_content - Write a script that writes into the file ls_cwd_content the result of the command ls -la
tail -n 1 iacta | cat >> iacta - Write a script that duplicates the last line of the file iacta
find . -name "*.js" -type f -delete - Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
