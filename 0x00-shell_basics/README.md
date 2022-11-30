task 0 pwd-prints working directory
task 1 ls - prints content list of my current working directory
task 2 cd - changes the current working directory
task 3 la or ls -a -prints the content list of the current working directory in long format
task 4 ls -la -List all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format
task 5  ls -al ist all files (even ones with names beginning with a period character, which are normally hidden) in the parent of the working directory in long format and group ids
task 6 mkdir -Create a script that creates a directory named my_first_directory in the /tmp/ directory
task 7 mv -Move the file betty from /tmp/ to /tmp/my_first_directory
task 8 rm - deletes the Betty file
task 9 rm -r - delete the my_first_directory
task 10 cd -  - changes the working directory to the previous one
task 11 ls -la . .. /boot - lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
task 12 file -prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
task 13 ln -s -Creates a symbolic link to /bin/ls, named __ls__ in the current working directory
task 14 cp -u* -copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that don't exist in the parent of the working directory or were newer than the versions in the parent of the working directory. 
task 15 Create a script that moves all files beginning with an uppercase letter to the directory /tmp/ assuming the directory /tmp/u exists when running the scripts
task 16 deletes all files in the current working directory that end with the character ~
task 17 creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory using only two spaces and lines
task 18 Write a command that lists all the files and directories of the current directory, separated by commas (,).

Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter or one digit
The listing should end with a new line
task 19 Create a magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.
