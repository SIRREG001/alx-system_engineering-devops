0-iam_betty switches the current user to betty
1-who_am_i prints the effective username of the current user
2-groups prints all groups the current user is part of
3-new_owner changes the owner of the file hello tp the user betty
4-empty creates an empty file called hello
5-execute executes permissions to the owner of the file hello
6-multiple_permissions adds execute permissions to the owner =, and the group owner and read permissions o
7-everybody adds execution permissions to the owner, the group owner, and other users to the file hello
8-James_Bond writes permissions that set the file hello as follows: owner: no permission at all; group: no permission at all; other users: all the permissions
9-John_Doe sets the mode of the file hello to -rwxr-x-wx 1 julien 23 Sep 20 14:25 hello
10-mirror_permissions sets the mode of the file hello the same as olleh's mode.
11-directories_permissions adds execute permissions to all subdirectories of the current directory for the owner, the group owner and all the users.
12-directory_permissions creates a directory called my_dir with permissions 751 in the working directory
13-change_group chnages the group owner to school for the file hello
100-change_owner_and_group changes the owner to vincent and the group owner to staff for all the files and directories in the working directory
101-symbolic_link_permissions changes the owner and group owner of _hello to vincent and staff respectively
