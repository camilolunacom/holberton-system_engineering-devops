# Project: 0x00. Shell, basics

Practice basic bash scripting. The following exercises have a script associated.

## Mandatory Tasks

### 0. Where am I?

**File:** `0-current_working_directory`

Print the absolute path name of the current working directory.

### 1. What’s in there?

**File:** `1-listit`

Display the contents list of the current directory.

### 2. There is no place like home

**File:** `2-bring_me_home`

Change the working directory to the user's home directory.

### 3. The long format

**File:** `3-listfiles`

Display current directory contents in long format.

### 4. Hidden files

**File:** `4-listmorefiles`

Display current directory contents, including hidden files, using lon format.

### 5. I love numbers

**File:** `5-listfilesdigitonly`

Display current directory contents in long format, with user and group IDs and including hidden files.

### 6. Welcome holberton

**File:** `6-firstdirectory`

Create a directory named `holberton` in `/tmp`.

### 7. Betty in Holberton

**File:** `7-movethatfile`

Move the file `betty` from `/tmp` to `/tmp/holberton`.

### 8. Bye bye Betty

**File:** `8-firstdelete`

Delete the file `betty`.

### 9. Bye bye Holberton

**File:** `9-firstdirdeletion`

Delete the directory `holberton` from `/tmp`.

### 10. Back to the future

**File:** `10-back`

Change the working directory to the previous one.

### 11. Lists

**File:** `11-lists`

List all files in the current directory, parent of the working directory and the `/boot` directory in that order.

### 12. File type

**File:** `12-file_type`

Print the type of the file `/tmp/iamafile`.

### 13. We are symbols, and inhabit symbols

**File:** `13-symbolic_link`

Create the `__ls__` symlink to `/bin/ls` in the current working directory.

### 14. Copy HTML files

**File:** `14-copy_html`

Copy all HTML (`.html`) files from the current working directory to the parent of the working directory. Only overwrite older versions of the files.

### 15. Let’s move

**File:** `15-lets_move`

Move all files beginning with an uppercase letter to `/tmp/u`, assuming the redictory already exists.

### 16. Clean Emacs

**File:** `16-clean_emacs`

Delete all files in the current working directory that end with `~`.

### 17. Tree

**File:** `17-tree`

Create the directories `welcome/`, `welcome/to/` and `welcome/to/holberton` in the current directory. The script can only include 2 spaces.

### 18. Life is a series of commas, not periods

**File:** `18-commas`

List all the files and directories of the current directory, separated by commas (`,`). Also:

- Directory names should en with `/`.
- Hidden files should be listed.
- The list should by alpha ordered, hidden files should be listed at the beginning.
- Only digits and letters are used to sort, digits come first.
- Assume all files will have at least one letter or one digit.
- The list should end with a new line.

## Advanced (Optional) Tasks

### 19. File type: Holberton

**File:** `holberton.mgc`

Create a magic file `holberton.mgc` that can be used with the command `file` to detect `Holberton` data files. `Holberton` data files always contain the string `HOLBERTON` at offset 0.

