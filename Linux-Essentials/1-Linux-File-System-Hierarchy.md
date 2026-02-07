# FHS is the Linux File System

What is FHS?The Filesystem Hierarchy Standard (FHS) is a reference describing the conventions used for the layout of a Unix-like operating system's filesystem. It's maintained by the Linux Foundation and defines the directory structure and directory contents in Linux distributions.Key Points:

Provides consistency across different Linux distributions
Makes it easier for users and software to predict file locations
Defines which directories are essential for system boot vs. which can be on separate partitions
Current version: FHS 3.0 (June 2015)

Core Principles of Linux Filesystem1. Everything is a File
In Linux, everything is treated as a file:

Regular files (documents, images, etc.)
Directories (special files containing other files)
Devices (hard drives, keyboards, mice) → /dev/sda, /dev/tty
Sockets (for inter-process communication)
Pipes (for data flow between processes)
Symbolic links (pointers to other files)
2. Single Hierarchical Tree

Unlike Windows (C:, D:), Linux has ONE root directory /
All storage devices are "mounted" into this single tree
Example: USB drive might be mounted at /mnt/usb or /media/username/usb
3. Case Sensitive

file.txt, File.txt, and FILE.TXT are three different files
Directory names are also case-sensitive
4. Hidden Files

Files/directories starting with . are hidden
Example: .bashrc, .config, .ssh
View with ls -a or ls -la
