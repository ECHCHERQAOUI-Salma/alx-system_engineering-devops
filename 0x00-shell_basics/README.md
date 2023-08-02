pwd is used to print the absolute path name of the current working directory
ls displays the contents list of your current directory.
cd changes the working directory to the user’s home directory.
ls -l displays current directory contents in a long format.
ls -la displays current directory contents, including hidden files, using the long format.
ls -na displays content of current directory, including hidden in long format with user and group IDs displayed numerically.
mkdir path/dir_name creates a directory in a specific path
mv dir path/dir moves a directory

rm path/file deletes a file in a specific path
rmdir deletes a directory
cd - changes the working directory to the previous one.
ls -la . .. lists all files;hidden in current directory and parent, in long format.
file file_name prints the type of the file
ln -s . _ls_ creates symbolic link in current directory
cp -u copy when source is newer than destination
cp [[:upper:]]* moves all files beginning with an uppercase letter
not cp but mv
rm *~ deletes all files in the current working directory that end with ~
mkdir -p makes directories with subdirectories at once
ls -Fma Append indicator (one of */=>@|) to entries (hidden also), separated by commas, alpha ordered
