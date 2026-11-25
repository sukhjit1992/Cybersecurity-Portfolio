# Linux File Permissions Management

## Project Overview

In this project, I learned how to manage file and directory permissions in Linux using command-line tools. I applied the principle of least privilege to understand how permissions are assigned to users, groups, and others.

The goal of this activity was to identify existing permissions, understand permission strings, and modify access to files and directories to help prevent unauthorized access.

## 1. Check File and Directory Details

I used Linux commands to view detailed information about files and directories, including their permissions and ownership.

The commands used in this activity included:

- `ls -l`
- `ls -ls`

## 2. Understanding Linux Permission Strings

I used the following file as an example:

`-rw-rw-r--`

The 10-character permission string provides information about the file type and access permissions.

- **1st character:** Identifies the file type. `-` represents a regular file, while `d` represents a directory.
- **2nd–4th characters:** Represent the permissions assigned to the owner.
- **5th–7th characters:** Represent the permissions assigned to the group.
- **8th–10th characters:** Represent the permissions assigned to others.

The permission symbols mean:

- `r` – Read permission
- `w` – Write permission
- `x` – Execute permission
- `-` – No permission

## 3. Change File Permissions

I used the Linux `chmod` command to modify file permissions and ensure that access was properly assigned.

## 4. Change Permissions on a Hidden File

I learned how to identify hidden files in Linux and modify their permissions using Linux commands.

The activity involved managing permissions for the hidden file `.project_x.txt`.

## 5. Change Directory Permissions

I used the `chmod` command to modify directory permissions and restrict access according to the organization's authorization requirements.

## Project Summary

Through this activity, I gained practical experience using Linux command-line commands to check file and directory details and manage permissions.

I learned how to interpret the 10-character permission string and use the `chmod` command to modify access permissions. By applying the principle of least privilege, I can help prevent unauthorized users from accessing or modifying files and directories.

## Skills Demonstrated

- Linux command line
- File and directory permissions
- `ls` commands
- `chmod` command
- Understanding permission strings
- Hidden file management
- Principle of Least Privilege
- Access control and authorization

---

**Project Category:** Cybersecurity

**Project Type:** Linux File Permissions Management

**Platform:** Linux
