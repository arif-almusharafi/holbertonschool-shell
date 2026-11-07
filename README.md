# Holberton School - Shell

Linux shell exercises from Holberton School. Each task is a short shell script or command in its own file, and the files are numbered by task.

## Projects

| Folder | Tasks | Topic |
| --- | --- | --- |
| [basics](basics/) | 0 - 17 | Moving around the file system, and creating, copying, moving, listing and deleting files and directories |
| [init_files_variables_and_expansions](init_files_variables_and_expansions/) | 0 - 14 | Aliases, `PATH`, local and global variables, and shell expansions (arithmetic, number conversions, `printf`) |
| [io_redirections_and_filters](io_redirections_and_filters/) | 0 - 26 | Input and output redirection, pipes, and filters to read, sort, search, count and reverse text |
| [permissions](permissions/) | 0 - 16 | Users and groups, file owners, and changing permissions with `chmod`, `chown` and `chgrp` |

## Example

```bash
# list files in the current directory (basics)
ls

# send the output of one command to another (io_redirections_and_filters)
ls | wc -l
```

## How to run

Make a task file executable, then run it:

```bash
chmod u+x file_name
./file_name
```

## Concepts practiced

- Working in the Linux terminal
- Files, directories and symbolic links
- Shell variables and expansions
- Redirections and pipes
- Users, groups and file permissions

## Author

Arif Almusharafi - [GitHub](https://github.com/arif-almusharafi)
