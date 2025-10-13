---
title: Implementation of File System and Memory Management in xv6
description: Implementation of file system features and memory management in the xv6 educational operating system.
summary: A project focused on implementing file system features and memory management in the xv6 operating system.
featured: featured.png
tags:
  - Operating Systems
  - File System
  - Memory Management
  - C Programming
  - System Programming
date: 2024-12-15
external_link: ''
---
As part of the Operating Systems course, I implemented **file system features and memory management** in the xv6 educational operating system. This project focused on two main aspects:

## File System Implementation
1. **System Call Development**: Added new system calls including `symlink()` for creating symbolic links and `readlink()` for reading symbolic links.
2. **Hard Link Support**: Enhanced the file system to support hard links between files, requiring modifications to the inode structure.
3. **File System Features**: Implemented various file system features including file permissions and directory manipulation.

## Memory Management
1. **Page Table Management**: Modified the page table management system to support memory mapping and unmapping.
2. **Memory Allocation**: Enhanced the memory allocator to handle dynamic memory allocation more efficiently.
3. **System Call Implementation**: Added system calls like `mmap()` and `munmap()` for memory mapping functionality.

Through this project, I gained practical experience in:
- Working with low-level system programming in C
- Understanding operating system internals through hands-on implementation
- Debugging complex system-level code
- Managing memory and file systems at the operating system level
