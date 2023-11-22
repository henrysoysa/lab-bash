Exercises
1. Using the echo command print in console "Hello World". Here is some info about echo command
echo "Hello World"


2. Create a new directory called new_dir.
mkdir "new_dir"


3. Delete/Remove the directory new_dir.
rm -rf "new_dir"


4. Copy the file sed.txt from the lorem folder and paste it to the folder lorem-copy folder.
cp lorem/sed.txt lorem-copy


5. Copy the other two files from the lorem folder to lorem-copy folder in just one line using semicolon ;.
cp lorem/at.txt lorem-copy ; cp lorem/lorem.txt lorem-copy


6. Show the sed.txt file content from the lorem folder.
cat lorem/sed.txt


7. Show the at.txt file and lorem.txt file contents from lorem folder.
cat lorem/at.txt && cat lorem/lorem.txt 


8. Print the first 3 rows in sed.txt file from lorem-copy folder.
head -3 lorem-copy/sed.txt

9. Print the last 3 rows in sed.txt file from lorem-copy folder.
tail -3 lorem-copy/sed.txt

10. Add Homo homini lupus. at the end of sed.txt file in the lorem-copy folder. Print the last 3 rows in sed.txt file from lorem-copy folder. You should see Homo homini lupus..
echo "Homo homini lupus" >> lorem-copy/sed.txt
tail -3 lorem-copy/sed.txt

11. sed command is used to replace the text in a file. Use the sed command to replace all occurances of et with ET in the file at.txt file present in the folder lorem. You can use the following link to refer to sed commands [https://www.linode.com/docs/guides/manipulate-text-from-the-command-line-with-sed/] Check the contents of the sed.txt file using cat command.
sed 's/et/ET/g' at.txt


12. Find who is the system user.
whoami

13. Find the current path of the directory you are in.
pwd

14. List all files with the extension .txt in lorem folder.
grep
ls *.txt

15. Count the rows in sed.txt file from lorem folder. Look concatenate cat and wc with the pipe |.
wc -l sed.txt | cat sed.txt

16. Count the files which start with lorem in all directories.
ls  lorem* | wc -l

