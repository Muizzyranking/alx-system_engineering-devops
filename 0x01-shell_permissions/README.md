[link]: https://github.com/Muizzyranking/alx-system_engineering-devops/tree/main/0x01-shell_permissions
# Description

This directory contains executable shell permission scripts. The scripts can be used to change permissions in the shell environment and here are the descriptions of the scripts.

## List of scripts and what they do.

| File name | Description |
| ----------- | ----------- |
| [0-iam_betty](https://github.com/Muizzyranking/alx-system_engineering-devops/0x01-shell_permissions/0-iam_betty) | script that switches the current user to the user `betty` |
| [1-who am i](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/1-who_am_i) | script that prints the effective username of the current user. |
| [10-mirror_permissions](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/10-mirror_permissions) | script that sets the mode of the file hello the same as olleh’s mode. (The files `hello` and `olleh` are in the working directory) |
| [100-change_owner_and_group](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/100-change_owner_and_group) | a script that changes the owner to `vincent` and the group owner to `staff` for all the files and directories in the working directory. |
| [101-symbolic_link_permissions](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/101-symbolic_link_permissions) | script that changes the owner and the group owner of `_hello` to `vincent` and `staff` respectively. The file `hello` is a symbolic link and is in the working directory |
| [102-if_only](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/102-if_only) | a script that changes the owner of the file `hello` in the working directory to `betty` only if it is owned by the user `guillaume` |
| [103-Star_Wars](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/103-Star_Wars) |  a script that will play the StarWars IV episode in the terminal. |
| [11-directories_permissions](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/11-directories_permissions) |  a script that switches the current user to the user `betty` |
| [12-directory_permissions](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/12-directory_permissions) | a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files would be unchanged |
| [13-change_group](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/13-change_group) | script that changes the group owner to school for the file `hello` in the working directory |
| [2-groups](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/2-groups) | script that prints all the groups the current user is part of |
| [3-new_owner](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/3-new_owner) |script that changes the owner of the file `hello` to the user `betty` |
| [4-empty](https://github.com/Muizzyranking/alx-system_engineering-devops/blob/main/0x01-shell_permissions/4-empty) | script that creates an empty file called `hello` |
| [5-execute](./5-execute) | script that adds execute permission to the owner of the file `hello` in the working directory |
| [6-multiple_permissions](./6-multiple_permissions) | script that adds execute permission to the owner and the group owner, and read permission to other users, to the file `hello` in the working directory |
| [7-everybody](./7-everybody) | script that adds execution permission to the owner, the group owner and the other users, to the file `hello` |
| [8-James_Bond](./8-James_Bond) | script that sets the permission to the file `hello` as follows: Owner and Group: no permission at all; Other users: all the permissions |
| [9-John_Doe](./9-John_Doe) |  script that sets the mode of the file `hello` to`-rwxr-x-wx` |

