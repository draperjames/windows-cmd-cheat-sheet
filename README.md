# Windows Command Line Cheat Sheet

## Basic IO

|Description | Command | args | Example|
| :--- | :--- | :--- | :--- |
|Make new directory |`mkdir <new directory name>` | /? | `mkdir photos`|
|Remove directory | `rmdir /s <directory to be deleted>`| /? | `rmdir /s photos`|
|Rename file |`ren <old name> <new name>`|/?| `ren photos my_photos`|

## Basic Navigation

|Description | Command | args | Example|
| :--- | :--- | :--- | :--- |
|Change current directory|`cd <destination>`| /?|   |
|Go to parent directory |`cd ..`|   |   |
|Go to user profile|`cd %userprofile%`|   |   |

## User Input

|Description | Command | args | Example|
| :--- | :--- | :--- | :--- |
| Collect user input | `set /p <var name>=<prompt text>`| `set /p id="Enter ID: "`|   |   |
|    |   |  |

## Running DLLs    

|Description | Command | args | Example|
| :--- | :--- | :--- | :--- |
|Run classic credentials manager | `rundll32.exe keymgr.dll, KRShowKeyMgr`|  /? |   |


## System

|Description | Command | args | Example|
| :--- | :--- | :--- | :--- |
| Shutdown | `shutdown /s /t 0` |   |   |
| Restart | `shutdown /r /t 0` |   |   |
|    |    |    |
