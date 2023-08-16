# 0x01. Shell, permissions

`DevOps` `Shell` `Bash`

## Description

Bash Scripts to solve project tasks.\
Jul 6, 2023 4:00 AM to Jul 7, 2023 4:00 AM.

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
| 0. My name is Betty | [0-iam_betty](0-iam_betty) | Switches the current user to the user `betty`. Command uses exactly 8 characters |
| 1. Who am I | [1-who_am_i](1-who_am_i) | Prints the effective username of the current user |
| 2. Groups | [2-groups](2-groups) | Prints all the groups the current user is part of |
| 3. New owner | [3-new_owner](3-new_owner) | Changes the owner of the file `hello` to the user `betty` |
| 4. Empty! | [4-empty](4-empty) | Creates an empty file called `hello` |
| 5. Execute | [5-execute](5-execute) | Adds execute permission to the owner of the file `hello` residing in the working directory |
| 6. Multiple permissions | [6-multiple_permissions](6-multiple_permissions) | Adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello` residing in the working directory |
| 7. Everybody! | [7-everybody](7-everybody) | Adds execution permission to the owner, the group owner and the other users, to the file `hello` residing in the working directory without using commans in command |
| 8. James Bond | [8-James_Bond](8-James_Bond) | Sets the permission to the file `hello` residing in the working directory (not using commas in command) as follows:<br><br>- Owner: no permission at all<br>- Group: no permission at all<br>- Other users: all the permissions |
| 9. John Doe | [9-John_Doe](9-John_Doe) | Sets the mode of the file `hello` residing in the working directory to `-rwxr-x-wx` without using commas  |
| 10. Look in the mirror | [10-mirror_permissions](10-mirror_permissions) | Sets the mode of the file `hello` to that of file `olleh` both of which are in the working directory |
| 11. Directories | [11-directories_permissions](11-directories_permissions) | Adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users not affecting regular files |
| 12. More directories | [12-directory_permissions](12-directory_permissions) | Creates a directory called `my_dir` with permissions `751` in the working directory |
| 13. Change group | [13-change_group](13-change_group) | Changes the group owner to `school` for the file `hello` residing in the working directory |
| 14. Owner and group | [100-change_owner_and_group](100-change_owner_and_group) | Changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory |
| 15. Symbolic links | [101-symbolic_link_permissions](101-symbolic_link_permissions) | Changes the owner and the group owner of `_hello` (a symbolic link) residing in the working directory to `vincent` and `staff` respectively |
| 16. If only | [102-if_only](102-if_only) | Changes the owner of the file `hello` residing in the working directory to `betty` only if it is owned by the user `guillaume` |
| 17. Star Wars | [103-Star_Wars](103-Star_Wars) | Plays the StarWars IV episode in the terminal |

## Authors

Felix Kimbu

## Version History

- 0.2
    - Minor optimizations
- 0.1
    - Initial Release
