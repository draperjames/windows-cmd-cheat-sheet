# Windows Command Line Cheat Sheet

## Basic IO

|Description | Command | args | Example|
|--- | --- | ---|
|Make new directory |`mkdir <new directory name>` | /? | `mkdir photos`|
|Remove directory | `rmdir /s <directory to be deleted>`| /? | `rmdir /s photos`|
|Rename file |`ren <old name> <new name>`|/?| `ren photos my_photos`|

## Basic Navigation

|Description | Command | args | Example|
|--- | --- | ---|
|Change current directory|`cd <destination>`| /?| |
|Go to parent directory |`cd ..`| | |
|Go to user profile|`cd %userprofile%`| | |

## User Input

| Description        | Command              | Example                             |
| -------------      |:---                  |:---                                 |
| Collect user input | `set /p <var name>=<prompt text>`| `set /p id="Enter ID: "`|
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
