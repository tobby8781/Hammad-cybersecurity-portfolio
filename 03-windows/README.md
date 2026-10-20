# Windows CLI and PowerShell

## Overview

This section documents my practical learning of Windows command-line fundamentals through TryHackMe.

The objective was to understand how to interact with Windows systems from the command line, navigate the filesystem, work with files and directories, and use command-line tools for basic system interaction and investigation.

## Environment

- TryHackMe
- Windows lab environment
- Windows Command Prompt

## Learning Objectives

- Understand the Windows command-line interface
- Navigate Windows directories from the command line
- Work with files and folders
- Understand Windows paths
- Use command-line utilities
- Understand basic Windows system information
- Develop foundational skills for Windows security investigation

## Topics Practised

### Windows Filesystem

I learned how Windows organizes files and directories and how paths are represented.

Example:

```text
C:\Users\Username\Documents
```

### Navigation and File Operations

Commands practised included:

```cmd
cd
dir
mkdir
copy
move
del
```

These commands were used to navigate directories, list contents, create folders, copy and move files, and delete files.

### System Investigation

I also practised basic Windows commands useful for identifying system information:

```cmd
whoami
hostname
ipconfig
tasklist
```

These commands can help identify the current user, hostname, network configuration, and running processes.

## Cybersecurity Relevance

Windows is widely used in organisations, making Windows command-line knowledge important for security operations and investigation.

Command-line skills can help analysts:

- Identify users and systems
- Check network configuration
- Review running processes
- Navigate files during investigations
- Perform basic system reconnaissance

## Key Lessons

- Windows uses drive letters such as `C:\`.
- `cd` changes the current directory.
- `dir` lists directory contents.
- `mkdir` creates directories.
- `copy` and `move` manage files.
- `del` removes files.
- `ipconfig` displays network configuration.
- `tasklist` displays running processes.

## Security Note

These commands are basic administrative and investigation tools. More advanced Windows security investigation will be covered later as I progress toward Security Analyst/SOC training.

## Windows PowerShell — TryHackMe Cyber Security 101

**Status: Completed the Windows PowerShell room.**

PowerShell is a command-line shell and scripting environment used to administer and inspect Windows systems. During this beginner learning, I practised PowerShell commands and explored module/repository-related commands.

Examples covered during practice:

```powershell
Get-Process
Get-Service
Get-Module -ListAvailable
Get-PSRepository
Find-Module
Test-NetConnection
```

- `Get-Process` lists processes.
- `Get-Service` lists Windows services.
- `Get-Module -ListAvailable` lists modules available on the system.
- `Get-PSRepository` displays registered PowerShell repositories.
- `Find-Module` searches for modules in a repository.
- `Test-NetConnection` tests connectivity to a host and port.

### Troubleshooting note

During the lab, a connection test to PowerShell Gallery on TCP port 443 returned `TcpTestSucceeded: False`. The repository was registered, but the connection test failed. Successful module download or installation was **not** confirmed.

## Cybersecurity Relevance

PowerShell can help an analyst identify the current user and computer, inspect processes and services, check module/repository configuration, and troubleshoot network connectivity. A process or service should not be labelled malicious based on its name alone; findings need context and corroborating evidence.

## Key Lessons

- Windows Command Prompt and PowerShell are different command-line environments.
- PowerShell commands commonly use a verb-noun naming convention, such as `Get-Process`.
- `Get-Process` and `Get-Service` inspect processes and services.
- A failed connectivity test does not by itself prove that a repository or module is unavailable.
- Lab results should be documented accurately, including errors and limitations.

## Status

- Windows CLI Basics — Completed
- Windows PowerShell (TryHackMe Cyber Security 101) — Completed
