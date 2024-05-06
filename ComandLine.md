# Table of Contents

- [How it Works](#how-it-works)
  - [How to Access](#how-to-access)
- [Linux File System Navigation](#linux-file-system-navigation)
  - [File System Hierarchy](#file-system-hierarchy)
  - [Current Directory (print working directory)](#current-directory-print-working-directory)
  - [List Contents](#list-contents)
  - [Change Directory](#change-directory)
  - [Relative and Absolute Paths](#relative-and-absolute-paths)
  - [Path Completion](#path-completion)
- [Linux is an Extensionless System](#linux-is-an-extensionless-system)
- [Linux is Case Sensitive](#linux-is-case-sensitive)
- [Spaces in Names](#spaces-in-names)
- [Hidden Files and Directories](#hidden-files-and-directories)
- [Manual Pages](#manual-pages)
  - [Main Commands Used in the Demo](#main-commands-used-in-the-demo)
  - [Summary](#summary)
- [File Manipulation](#file-manipulation)
  - [Making a Directory](#making-a-directory)
  - [Removing a Directory](#removing-a-directory)
  - [Creating a Blank File](#creating-a-blank-file)
  - [Copying a File or Directory](#copying-a-file-or-directory)
  - [Moving a File or Directory](#moving-a-file-or-directory)
  - [Removing a File (and non-empty Directories)](#removing-a-file-and-non-empty-directories)
- [Cheat Sheet](#cheat-sheet)


## The Command Line

The command line is a text-based interface for interacting with a computer's operating system. It allows users to issue commands to the computer by typing text commands rather than using a graphical interface. The command line provides direct access to the system, enabling users to perform various tasks such as file manipulation, software installation, and system configuration.

### How it Works:

- When a command is entered in the command line interface, it is interpreted by the shell, which is a program that acts as an intermediary between the user and the operating system.
- The shell parses the command, identifies the executable program associated with it, and then executes the program with any specified options and arguments.
- After execution, the output of the command is displayed in the terminal window.

### How to Access:

- To access the command line on Linux, open a terminal emulator such as Terminal, Konsole, or GNOME Terminal.
- On Windows, open Command Prompt or PowerShell from the Start menu or by using keyboard shortcuts like Win + R and typing "cmd" or "powershell".

---

# Linux File System Navigation

### File System Hierarchy

Linux organizes files in a hierarchical structure starting from the root directory (/). Key directories include:

- `/bin`: Binary files
- `/etc`: System configuration files
- `/home`: User directories
- `/var`: Variable data

### Current Directory (print working directory)

You can check your current directory using the `pwd` command.

### List Contents

Use `ls` to list the contents of a directory. Options like `-l` provide detailed information such as permissions, owner, size, and modification time.

### Change Directory

Move to a different directory using `cd`. Typing `cd` without arguments takes you to your home directory.

### Relative and Absolute Paths

Paths can be relative (specified from your current directory) or absolute (specified from the root directory). Use `.` to represent the current directory and `..` to represent the parent directory.

### Path Completion

Pressing the Tab key can help complete directory and file names, saving time and reducing typing errors.

---

## Linux is an Extensionless System

- Linux ignores file extensions to determine file types.
- Unlike Windows, where extensions are crucial for file identification.
- Use the `file` command to identify file types regardless of their extensions.

## Linux is Case Sensitive

- Linux distinguishes between uppercase and lowercase letters in filenames.
- This is different from systems like Windows, which are case-insensitive.
- Pay attention to letter casing when using commands and referring to files.

## Spaces in Names

- Spaces in file and directory names can cause issues on the command line.
- Use quotes or escape characters (\) to handle names with spaces.
  - Example using quotes: `cd 'Holiday Photos'`
  - Example using escape character: `cd Holiday\ Photos`

## Hidden Files and Directories

- Files or directories starting with a dot (.) are considered hidden in Linux.
- Commonly used for configuration files or to prevent cluttering in directory listings.
- Use `ls -a` to list all files, including hidden ones.

---

## Manual Pages

Manual pages, commonly referred to as man pages, are a comprehensive set of documentation in Unix-like operating systems that provide detailed information about various commands, utilities, functions, and file formats. They serve as a vital resource for users to understand the usage and functionality of commands available in the command-line interface.

### Main Commands Used in the Demo

- `man <command>`: Displays the manual page for the specified command, providing detailed information on its usage and options.
- `man -k <search term>`: Performs a keyword search across all manual pages to find commands related to the specified search term.
- `/<term>`: Within a manual page, performs a search for the specified term, allowing users to quickly locate relevant information within the page.

### Summary

Manual pages, or man pages, are comprehensive documentation in Unix-like systems providing detailed information about commands, utilities, and functions. Users can access manual pages using the `man` command to view documentation for specific commands or perform keyword searches using `man -k`. The ability to search within manual pages using `/` followed by a term enhances usability, enabling

## File Manipulation

### Making a Directory:

- Use `mkdir` to create directories and organize files hierarchically.
- Understand relative and absolute paths for directory creation.

### Removing a Directory:

- Use `rmdir` to remove empty directories.

### Creating a Blank File:

- The `touch` command creates empty files.
- It's also used to modify file access and modification times.

### Copying a File or Directory:

- Duplicate files or directories with the `cp` command.
- Use `-r` for recursive copying of directories.

### Moving a File or Directory:

- The `mv` command moves files or directories.
- Renaming is accomplished by moving to the same directory with a different name.

### Removing a File (and non-empty Directories):

- The `rm` command deletes files and directories.
- Use `-r` for recursive removal of non-empty directories. 

## Cheat Sheet

[Cheat Sheet](https://ryanstutorials.net/linuxtutorial/cheatsheet.php)

---