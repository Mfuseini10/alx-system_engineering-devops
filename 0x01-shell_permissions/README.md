# 0x01. Shell, Permissions

## General Requirements
* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file, at the root of the folder of the project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your files must be executable

## Tasks
[0. My name is Betty](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty)

Create a script that switches the current user to the user betty.
* You should use exactly 8 characters for your command (+1 character for the new line)
* You can assume that the user betty will exist when we will run your script

[1. Who am I](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i)

Write a script that prints the effective username of the current user.

[2. Groups](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups)

Write a script that prints all the groups the current user is part of.

[3. New owner](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner)

Write a script that changes the owner of the file hello to the user betty.

[4. Empty!](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty)

Write a script that creates an empty file called hello.

[5. Execute](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute)

Write a script that adds execute permission to the owner of the file hello.
* The file hello will be in the working directory

[6. Multiple permissions](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions)

Write a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
* The file hello will be in the working directory

[7. Everybody!](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody)

Write a script that adds execution permission to the owner, the group owner and the other users, to the file hello
* The file hello will be in the working directory
* You are not allowed to use commas for this script

[8. James Bond](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond)
Write a script that sets the permission to the file hello as follows:
* Owner: no permission at all
* Group: no permission at all
* Other users: all the permissions

The file hello will be in the working directory You are not allowed to use commas for this script

[9. John Doe](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe)

Write a script that sets the mode of the file hello to this:

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
* The file hello will be in the working directory
* You are not allowed to use commas for this script

[10. Look in the mirror](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions)

Write a script that sets the mode of the file hello the same as olleh’s mode.
* The file hello will be in the working directory
* The file olleh will be in the working directory

Note: the mode of olleh will not always be 664. Make sure your script works for any mode.

[11. Directories](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions)

Create a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

[12. More directories](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions)

Create a script that creates a directory called my_dir with permissions 751 in the working directory.

[13. Change group](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group)

Write a script that changes the group owner to school for the file hello
*The file hello will be in the working directory
