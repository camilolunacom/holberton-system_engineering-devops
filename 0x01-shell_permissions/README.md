# Project: 0x01. Shell, permissions

Practice bash permissions.

## Mandatory Tasks

### 0. My name is Betty

File: `0-iam_betty`

Change user id to `betty`.

### 1. Who am I

File: `1-who_am_i`

Print the userid of the current user.

### 3. New owner

File: `3-new_owner`

Change the owner of the file `hello` to the user `betty`.

### 4. Empty!

File: `4-empty`

Create an empty file called `hello`.

### 5. Execute

File: `5-execute`

Add execute permissions to the owner of the file `hello`.

### 6. Multiple permissions

File: `6-multiple_permissions`

Add execute permission to the owner and the group owner, and read permissions to other users, to the file `hello`.

### 7. Everybody!

File: `7-everybody`

Add execution permission to the owner, the group owner and the other users, to the file `hello`.

### 8. James Bond

File: `8-James_Bond`

Set the permission to the file `hello`: no permissions for owner, no permissions for group, all permissions for other users.

### 9. John Doe

File: `9-John_Doe`

Set the mode of the file `hello` to:
```bash
-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
```

### 10-mirror_permissions

File: `10-mirror_permissions`

Set the mode of the file `hello` the same as `olleh`'s mode.

### 11. Directories

File: `11-directories_permissions`

Add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.

### 12. More directories

File: `12-directory_permissions`

Create a directory called `dir_holberton` with permissions 751 in the working directory.

### 13. Change group

File: `13-change_group`

Change the group owner to `holberton` for the file `hello`.

### 14. Owner and group

File: `14-change_owner_and_group`

Change the owner to `betty` and the group owner to `holberton` for all the files and directories in the working directory.

### 15. Symbolic links

File: `15-symbolic_link_permissions`

Change the owner and group owner of the file `_hello` to `hetty` and `holberton` respectively. The file `_hello` is a symbolic link in the working directory.

### 16. If only

File: `16-if_only`

Change the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.

## Advanced (Optional) Tasks

### 17. Star Wars

File: `100-Star_Wars`

Play StarWard IV episode in the terminal.

### 18. RTFM

File: `101-man_holberton`

Create a man page.
