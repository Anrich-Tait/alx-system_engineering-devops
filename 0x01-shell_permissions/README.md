This directory is used to store all the scripts for the 0x01 Shell Permissions project from ALX.
The scripts are as follows:
0. 0-iam_betty : switches the current user to the user "betty" using $su - user
1. 1-who_am_i : prints the username of current user using $whoami 
2. 2-groups : lists the groups user is in using $groups
3. 3-new_owner : changes the owner of the "hello" file to "betty" using $chown
4. 4-empty : creates an empty file using $touch
5. 5-execute : Adds execute permission to the file owner using $chmod u+x 
6. 6-multiple_permissions: adds execute permission to the owner and group owner, and read permission to all other users using $chmod u+x
7. 7-everybody : adds execution permission to all users using $chmod
8. 8-James_Bond : sets permission of "hello" file to only let other users have permissions using $chmod 007
9. 9-John_Doe : sets file mode using $chmod 754
10. 10-mirror_premissions : sets the "hello" file to have the same mode as the "olleh" file using $chmod --reference
11. 11-directories_permissions : adds execute permission to all subdirectories of the current directory without affecting regular files using $find
12. 12-directory_premissions : creates a directory called my_dir with permissions 751 using $mkdir
13. 13-change_group : changes the group owner of file "hello" to school using $chgrp 
14. 100-change_owner_and_group : changes the owner to vincent and group owner to staff for all files and directories in the current working directory using $chown -R
15. 101-symbolic_link_permissions : changes the owner and group owner of _hello to vincent and staff respectively using $chown -h
16. 102-if_only: uses an if statement to change the owner of file "hello" to "betty" only if the file is owned by the user "guilluame
17. 103-Star_Wars :
