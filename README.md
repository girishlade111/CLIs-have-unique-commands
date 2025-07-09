# CLIs-have-unique-commands

Providing a comprehensive list of all CLI (Command-Line Interface) commands is challenging due to the vast number of operating systems, shells, and utilities available. However, I can give you a broad overview of common commands across various Unix-like systems (including Linux and macOS) and Windows. I'll also include some information on how to find more commands and how to use them.
Unix-like Systems (Linux, macOS)
Navigation and File Management

* cd: Change directory.
* pwd: Print working directory.
* ls: List files and directories.
* mkdir: Make a directory.
* rm: Remove files or directories.
* rmdir: Remove empty directories.
* cp: Copy files or directories.
* mv: Move or rename files or directories.
* touch: Create a new empty file or update the timestamp of an existing file.

File Viewing and Editing

* cat: Concatenate and display files.
* less: View a file one page at a time.
* nano/vim: Text editors.

System Information

* uname: Print system information.
* hostname: Display or set the system's hostname.
* whoami: Print the username associated with the current effective user ID.
* uptime: Show how long the system has been running.
* free: Display memory and disk usage.

Process Management

* ps: Report a snapshot of the current processes.
* top/htop: Display and update information about the running processes.
* kill: Send a signal to a process.
* bg/fg: Manage background and foreground jobs.

Networking

* ping: Test network connectivity.
* ssh: Secure Shell, a cryptographic network protocol for secure command-line, login, and data transfer.
* scp: Securely copy files over a network.
* curl/wget: Download files from the internet.

Security and Permissions

* chmod: Change file mode bits.
* chown: Change file owner and group.
* sudo: Execute a command with superuser privileges.

Miscellaneous

* man: Display the manual for a command or function.
* echo: Output text to the screen or a file.
* alias: Create a custom shortcut for a longer command.

Windows Command Prompt (Cmd)
Navigation and File Management

* cd: Change directory.
* dir: List files and directories.
* mkdir: Make a directory.
* del: Delete one or more files.
* copy: Copy one or more files to another location.
* move: Move one or more files from one location to another.
* rename: Rename a file or files.

System Information

* systeminfo: Display detailed configuration information about the computer.
* hostname: Display the hostname of the computer.
* ver: Display the Windows version.

Process Management

* tasklist: Display a list of currently running processes.
* taskkill: Kill a process.

Networking

* ping: Test network connectivity.
* netstat: Display active TCP connections, routing tables, and interface statistics.

Security and Permissions

* runas: Run a tool or program under a different user account.

Miscellaneous

* cls: Clear the command prompt screen.
* echo: Output text to the screen or a file.
* doskey: Recall commands, edit command lines, and create macros.

PowerShell (Windows)
PowerShell is a task automation and configuration management framework from Microsoft, consisting of a command-line shell and associated scripting language built on .NET.

* Most Cmd commands work in PowerShell.
* Additional cmdlets (pronounced "command-lets") for various tasks, such as Get-Process, Get-ChildItem, Invoke-WebRequest, etc.

Finding More Commands

* Use man <command> in Unix-like systems to learn more about a specific command.
* Use <command> --help or <command> /? in Windows to see the help for a command.
* Explore online documentation and forums for specific tasks or operating systems.

Example Use Cases
To list files in a directory in Unix-like systems:
bashDownloadCopy code Wrapls -l
To list files in a directory in Windows Cmd:
cmdDownloadCopy code Wrapdir
To download a file using curl in Unix-like systems or Windows:
bashDownloadCopy code Wrapcurl -O https://example.com/file.txt
To create a new directory in both Unix-like systems and Windows:
bashDownloadCopy code Wrapmkdir new_directory
Writing Scripts
You can automate tasks by writing scripts. For Unix-like systems, you can use Bash or other shell scripting languages. For Windows, you can use Batch files or PowerShell scripts.
For example, a simple Bash script to backup a directory:
bashDownloadCopy code Wrap#!/bin/bash

# Backup a directory
tar -czf backup.tar.gz /path/to/directory
To run this script, save it to a file (e.g., backup.sh), make it executable with chmod +x backup.sh, and then execute it with ./backup.sh.
A simple PowerShell script to list running processes:
powershellDownloadCopy code Wrap# List running processes
Get-Process
Save this to a file with a .ps1 extension and run it in PowerShell.
This is just a small sample of what's available. The CLI is a powerful tool, and mastering it can greatly enhance your productivity.
