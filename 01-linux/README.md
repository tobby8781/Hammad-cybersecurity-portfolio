# Linux CLI Basics

## Overview

This project documents my practical learning of Linux command-line fundamentals through TryHackMe.

The objective was to become comfortable navigating a Linux filesystem, locating files, working with directories, and reading files from the command line.

## Environment

- TryHackMe
- AttackBox
- Linux

## Topics Practised

- Linux filesystem
- Working directories
- Absolute paths
- Relative paths
- Hidden directories
- File discovery
- Directory navigation
- Reading files
- Command-line operations

## Commands Practised

```bash
pwd
ls
cd
find
cat
```

## Practical Exercise

I practised locating files from the command line and navigating to files stored inside nested and hidden directories.

Example workflow:

```bash
find ~ -name mission_brief.txt
cat /path/to/mission_brief.txt
```

This helped me understand the difference between locating a file and reading its contents, as well as the importance of absolute and relative paths.

## Cybersecurity Relevance

Linux command-line skills are important for cybersecurity because many security tools, servers, logs, and investigation environments are Linux-based.

These fundamentals will support later work in:

- Security operations
- Log analysis
- Network investigation
- Threat detection
- Incident response
- SOC analysis

## Key Lessons

- `pwd` shows the current working directory.
- `ls` lists files and directories.
- `cd` changes the current directory.
- `find` can locate files and directories.
- `cat` displays file contents.
- Hidden Linux directories commonly begin with a dot (`.`).
- Linux commands are generally case-sensitive.

## Status

**Completed**
