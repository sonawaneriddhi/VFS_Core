# VirtualFileSystem - Core
This project emulates file system functionality to create a virtual environment where users can perform file operations without interacting with a real disk

Virtual File System (VFS) – Purely Implementation in C

## Overview :

This project is a custom implementation of a Virtual File System (VFS) that simulates the core functionality of the Linux/UNIX file system.
It includes a custom shell to interact with the virtual environment. 
As the name suggests, the system is virtual because all file records are maintained in primary memory (RAM), making them temporary and non-persistent after termination.
The project provides a practical understanding of system calls, file handling, memory management, and OS internals.

## The project provides hands-on understanding of:

1. File handling
2. System calls
3. Memory management
4. Operating System internals

### Key Features
        Custom Data Structures
        Implemented all major file system components from scratch, including:  
            Inode & Inode Table
            File Table
            User Area (UAREA)
            User File Descriptor Table (UFDT)
            Super Block
            Disk Inode List Block
            Data Blocks
            Boot Block

### System Call Implementations
        Developed core file system calls using custom logic inspired by UNIX algorithms:
        open, close, read, write, lseek
        create, rm, ls
        stat
          
### Custom Shell Interface

### User-friendly CLI for executing commands.

### Provides real-time interaction with the VFS
