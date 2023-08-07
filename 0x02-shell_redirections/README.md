echo displays line of text
\ prevents the next character from being interpreted as a special character
cat concatenate files and print on the standard output
"cat" concatenate files and print on the standard output
tail displays the last 10 lines of a file
head displays the first 10 lines of a file
head -n N file_name | tail -n +N print the N line

Write a script that creates a file \*\'Best School\'\*$\?\*\*\*\*\*:)
ls -la > ls_cwd_content writes into ls_cwd_content result of ls -la
tail --lines=1 iacta >> iacta duplicates the last line of iacta
find . -name *.js -type f -delete deletes js files from directory and it's subdirectories
find . -type d | wc -l counts the numberd of directories and subdirectories in current folder
ls -lt | head list the newer 10 files each in line
ls -RAl | grep drw | wc -l do the task 11
sort | uniq -u takes a list of words as input and prints unique ones
grep root /etc/passwd Display lines containing the patten “root” from passwd
grep bin /etc/passwd | wc -l Display the number of lines that contain “bin” in passwd
grep -A 3 root /etc/passwd Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
grep -v bin /etc/passwd Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Display all lines of the file /etc/ssh/sshd_config starting with a letter
tr A Z | tr c e Replace all characters A and c from input to Z and e respectively
tr -d c | tr -d C removes all letters c and C from input
rev reverse its input.
cat /etc/passwd | cut -d: -f 1,6 | sort  displays all users and their home directories, sorted by users
find . -empty | rev | cut -d/ -f 1 finds all empty files and directories in the current directory and all sub-directories
lists all the files with a .gif
