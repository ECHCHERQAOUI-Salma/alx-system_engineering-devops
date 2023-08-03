su betty switches the current user to betty
whoami prints the effective username of the current user.
groups prints all the groups the current user is part of.
sudo chown changes the owner of the file.
touch creates an empty file.
chmod u+x file_name adds execute permission to the owner of the file
chmod u+x,g+x,o+r add multiple permissions
chmod 111 adds execution permission to the owner, the group owner and the other users
chmod 007 adds all permissions to other users, no permissions for user and group
chmod 753 sets -rwxr-x-wx permissions
chmod --reference copy other file permissions
chmod -R change permissions for folder and subfolders
mkdir -m 751 my_dir creates directory and set his permissions
chgrp changes the group ownership
