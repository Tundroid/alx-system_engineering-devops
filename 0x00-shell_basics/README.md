# 0x00. Shell, basics

`DevOps` `Shell` `Bash`

## Description

Bash Scripts to solve project tasks.\
Jul 5, 2023 4:00 AM to Jul 6, 2023 4:00 AM.

## Getting Started

### Prerequisites

- Ubuntu 20.04 LTS
- Also works on Kali GNU/Linux Rolling 2023.2
- May work on other distros and / or versions but not tested.

### Installing

- Clone the repository to your environment
- Make sure to have executable permission on each bash script
  - You can make script executable using `chmod u+x script_file_name`

### Executing script

- `./script_file_name`

### Details

- *All tasks are completed without using ``backticks (`)``, `&&`, `||` or `;`*
- *All bash scripts contain only two lines; line 1 (`#!/bin/bash`) and line 2 for the command(s)*

| Task | File(s) | Description |
|---|---|---|
| 0. Where am I? | [0-current_working_directory](0-current_working_directory) | Prints the absolute path name of the current working directory |
| 1. What’s in there? | [1-listit](1-listit) | Lists contents of the current directory |
| 2. There is no place like home | [2-bring_me_home](2-bring_me_home) | Changes the working directory to the user’s home directory |
| 3. The long format | [3-listfiles](3-listfiles) | Lists current directory contents in a long format |
| 4. Hidden files | [4-listmorefiles](4-listmorefiles) | Lists current directory contents, including hidden files (starting with `.`) in long format |
| 5. I love numbers | [5-listfilesdigitonly](5-listfilesdigitonly) | Lists current directory contents (including hidden files) in;<br>- Long format<br>- With user and group IDs displayed numerically|
| 6. Welcome | [6-firstdirectory](6-firstdirectory) | Creates a directory named `my_first_directory` in the `/tmp/` directory |
| 7. Betty in my first directory | [7-movethatfile](7-movethatfile) | Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory` |
| 8. Bye bye Betty | [8-firstdelete](8-firstdelete) | Deletes the file `betty` from `/tmp/my_first_directory` |
| 9. Bye bye My first directory | [9-firstdirdeletion](9-firstdirdeletion) | Deletes the directory `my_first_directory` from `/tmp` |
| 10. Back to the future | [10-back](10-back) | Changes the working directory to the previous one |
| 11. Lists | [11-lists](11-lists) | Lists all files (hidden files also) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format |
| 12. File type | [12-file_type](12-file_type) | Prints the type of the file named  `iamafile` residing in `/tmp` |
| 13. We are symbols, and inhabit symbols | [13-symbolic_link](13-symbolic_link) | Creates a symbolic link to `/bin/ls`, named `__ls__` in the current working directory |
| 14. Copy HTML files | [14-copy_html](14-copy_html) | Copies all the HTML (`.html`) files from the current working directory to the parent of the working directory, but only copy files that do not exist in the parent of the working directory or are newer than the versions in the parent of the working directory |
| 15. Let’s move | [100-lets_move](100-lets_move) | Moves all files beginning with an uppercase letter to the directory `/tmp/u` |
| 16. Clean Emacs | [101-clean_emacs](101-clean_emacs) | Deletes all files in the current working directory that end with the character `~` |
| 17. Tree | [102-tree](102-tree) | Creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory using only two spaces in command |
| 18. Life is a series of commas, not periods | [103-commas](103-commas) | Lists all the files and directories of the current directory, separated by commas (`,`).<br>- Directory names end with a slash (`/`)<br>- Files and directories starting with a dot (`.`) are listed<br>- The listing is alpha ordered, except for the directories `.` and `..` which are listed at the very beginning<br>- Only digits and letters are used to sort; Digits come first<br>- The listing ends with a new line |
| 19. File type: School | [school.mgc](school.mgc)<br>[school](school)<br>[19-create_magic_file](19-create_magic_file) | Creates a magic file `school.mgc` (by compiling `school` file) that can be used with the command `file` to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0. |

## Help

Execute `./19-create_magic_file` on your environment just to be sure to have the correct working version of `school.mgc` for you.

## Authors

Felix Kimbu

## Version History

- 0.2
    - Minor optimizations
- 0.1
    - Initial Release
