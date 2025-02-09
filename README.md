# Linux Project - File Permissions

## Project Overview
In this project, I learned how to check and change file and folder permissions in Linux using different commands. My goal was to make files more secure and control who can access them.

## Technologies Used
- Linux Commands (e.g., `chmod`, `chown`, `ls`)
- Bash Shell (for scripting and command execution)

## Features
- **Checking file and directory permissions**: Listing file contents with detailed permission information.
- **Modifying file permissions**: Using `chmod` to update file permissions for different users.
- **Changing hidden file permissions**: Modifying permissions for hidden files.
- **Directory permissions**: Adjusting permissions for specific users and groups.

## Current File Permissions
This section displays the file structure of the `/home/researcher2/projects` directory and the permissions of the files and subdirectory it contains.

- **project_k.txt**  
  - User = read, write  
  - Group = read, write  
  - Other = read, write

- **project_m.txt**  
  - User = read, write  
  - Group = read  
  - Other = none

- **project_r.txt**  
  - User = read, write  
  - Group = read, write  
  - Other = read

- **project_t.txt**  
  - User = read, write  
  - Group = read, write  
  - Other = read

- **.project_x.txt** (hidden file)  
  - User = read, write  
  - Group = write  
  - Other = none

## Subdirectory: drafts
- **drafts directory**  
  - User = read, write, execute  
  - Group = execute  
  - Other = none
