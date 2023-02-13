# 0x02-shell_redirections

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
[0. Hello World](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/0-hello_world)

Write a script that prints “Hello, World”, followed by a new line to the standard output.

[1. Confused smiley](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/1-confused_smiley)

Write a script that displays a confused smiley "(Ôo)'.

[2. Let's display a file](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/2-hellofile)

Display the content of the /etc/passwd file.

[3. What about 2?](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/3-twofiles)

Display the content of /etc/passwd and /etc/hosts.

[4. Last lines of a file](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/4-lastlines)

Display the last 10 lines of /etc/passwd
* Tips: “Thinks of it as a cat, what is at the end of it?”

[5. I'd prefer the first ones actually](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/5-firstlines)

Display the first 10 lines of /etc/passwd

[6. Line #2](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/6-third_line)

Write a script that displays the third line of the file iacta.

The file iacta will be in the working directory
* You’re not allowed to use sed
* Note: The output will differ, depending on the content of the file iacta.

[7. It is a good file that cuts iron without making a noise](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/7-file)

Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

[8. Save current state of directory](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/8-cwd_state)

Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

[9. Duplicate last line](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/9-duplicate_last_line)

Write a script that duplicates the last line of the file iacta

* The file iacta will be in the working directory

[10. No more javascript](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/10-no_more_js)

Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

[11. Don't just count your directories, make your directories count](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/11-directories)

Write a script that counts the number of directories and sub-directories in the current directory.
*The current and parent directories should not be taken into account
*Hidden directories should be counted

[12. What’s new](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/12-newest_files)

Create a script that displays the 10 newest files in the current directory.

Requirements:
* One file per line
* Sorted from the newest to the oldest

[13. Being unique is better than being perfect](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/13-unique)

Create a script that takes a list of words as input and prints only words that appear exactly once.
* Input format: One line, one word
* Output format: One line, one word
* Words should be sorted

[14. It must be in that file](https://github.com/Mfuseini10/alx-system_engineering-devops/blob/master/0x02-shell_redirections/14-findthatword)

Display lines containing the pattern “root” from the file /etc/passwd
