# Operating System Security

## Overview

This section documents my foundational learning of operating system security through TryHackMe.

The objective was to understand how operating systems can be protected, how users and permissions are managed, and why the operating system is an important security boundary.

## Environment

- TryHackMe
- Windows and Linux concepts
- Practical security learning environment

## Learning Objectives

- Understand operating system security fundamentals
- Understand user accounts and privileges
- Understand permissions and access control
- Understand authentication
- Understand system hardening
- Understand common operating system security risks
- Understand the importance of security updates
- Understand the role of security controls

## Topics Studied

### Authentication

Authentication is the process of verifying the identity of a user or system.

Examples include:

- Password authentication
- Multi-factor authentication
- Biometrics
- Security keys

Strong authentication helps prevent unauthorized access.

### Authorization and Privileges

After a user is authenticated, the operating system determines what resources they are allowed to access.

Different users may have different privileges.

This principle is important because giving users unnecessary privileges can increase the impact of a compromise.

### Least Privilege

The principle of least privilege means users and processes should receive only the permissions necessary to perform their tasks.

This limits the potential damage if an account or application is compromised.

### File and Resource Permissions

Operating systems use permissions to control access to files, directories, applications, and other resources.

Understanding permissions is important when investigating unauthorized access or privilege escalation.

### System Hardening

System hardening involves reducing the attack surface of a system.

Examples include:

- Removing unnecessary software
- Disabling unnecessary services
- Applying security updates
- Using strong authentication
- Restricting user privileges
- Configuring firewalls
- Monitoring system activity

### Security Updates and Patching

Keeping operating systems and applications updated is an important security practice.

Security patches can address vulnerabilities that attackers may otherwise exploit.

### Pre-OS Boot Security

I learned that the pre-operating-system boot process can be an attractive target because it executes before the operating system and its security controls are fully running.

Compromising firmware or the boot process can potentially provide an attacker with highly privileged and persistent control.

## Common Operating System Security Risks

Examples of operating system security risks include:

- Weak passwords
- Excessive user privileges
- Unpatched vulnerabilities
- Misconfigured permissions
- Unnecessary services
- Malicious software
- Unauthorized accounts
- Compromised credentials
- Insecure configurations
- Boot or firmware-level attacks

## Defensive Controls

Important defensive measures include:

- Strong authentication
- Multi-factor authentication
- Least privilege
- Regular patching
- Endpoint protection
- Host-based firewalls
- Secure configuration
- Account management
- Logging and monitoring
- Regular security assessments

## Cybersecurity Relevance

Operating system security is fundamental to cybersecurity.

Security analysts need to understand how normal systems operate so that they can recognize abnormal or potentially malicious behaviour.

These concepts are relevant to:

- Security Operations Centres (SOC)
- Incident Response
- Endpoint Security
- Digital Forensics
- System Administration
- Vulnerability Management
- Threat Detection

## Key Lessons

- The operating system is a critical security boundary.
- Authentication and authorization serve different purposes.
- Least privilege reduces the potential impact of compromised accounts.
- Unpatched systems can expose organizations to known vulnerabilities.
- Secure configuration reduces the attack surface.
- Security monitoring helps identify suspicious activity.
- Security must be considered from the boot process through the running operating system.

## Practical Evidence

Screenshots and practical exercises demonstrating my learning will be added here as appropriate.

Sensitive information, credentials, tokens, and challenge flags will not be published.

## Status

**Completed**

## Learning Platform

TryHackMe
