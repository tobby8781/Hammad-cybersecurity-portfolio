# Computer Fundamentals

## Overview

This section documents my foundational learning of computer systems and technologies through TryHackMe.

The objective was to understand how modern computer systems work, including hardware components, operating systems, workstations, mobile devices, virtualization, and cloud computing.

## Learning Platform

- TryHackMe
- Computer Fundamentals

## Topics Studied

### Computer Hardware

I learned the basic components that make up a computer system and their roles.

Key components include:

- CPU
- RAM
- Storage
- Motherboard
- GPU
- Power supply
- Input and output devices

Understanding hardware is important because cybersecurity professionals need to understand the systems they are protecting and investigating.

### Workstations

I learned about workstation computers and how they differ from standard consumer computers.

Workstations are designed for professional and resource-intensive workloads and may include features such as:

- ECC RAM
- Professional-grade hardware
- Certified drivers
- Higher-performance processors
- Dedicated graphics capabilities

### Mobile Devices

I learned about the basic characteristics of smartphones and other mobile computing devices, including their emphasis on power efficiency, portability, and integrated hardware.

### Operating Systems

An operating system provides the software layer that manages computer hardware and allows applications and users to interact with the system.

Examples include:

- Windows
- Linux
- macOS
- Android
- iOS

Understanding operating systems is fundamental to cybersecurity because security controls, permissions, processes, and applications operate within an operating-system environment.

---

# Virtualisation Fundamentals

## What is Virtualisation?

Virtualisation is a technology that allows a physical computer to run one or more virtual computers, known as virtual machines.

A virtual machine can have its own:

- Operating system
- CPU allocation
- Memory allocation
- Storage
- Network configuration

Virtualisation allows organizations and individuals to run multiple environments on the same physical hardware.

## Virtual Machines

A virtual machine provides an isolated environment where an operating system and applications can run.

This can be useful for:

- Testing
- Development
- Training
- Cybersecurity laboratories
- Server consolidation
- Running different operating systems

## Cybersecurity Relevance

Virtualisation is particularly useful in cybersecurity because analysts and security researchers can create isolated environments for testing and learning without directly affecting their primary systems.

The TryHackMe AttackBox is an example of a practical environment used for cybersecurity learning.

---

# Cloud Computing Fundamentals

## What is Cloud Computing?

Cloud computing provides computing resources and services over a network, usually the internet.

Cloud services can provide:

- Computing power
- Storage
- Networking
- Databases
- Applications
- Security services

Cloud computing allows organizations to use computing resources without necessarily owning and maintaining all of the physical infrastructure themselves.

---

# IaaS — Infrastructure as a Service

IaaS provides fundamental computing infrastructure through the cloud.

Examples of resources include:

- Virtual machines
- Storage
- Networking
- Virtual firewalls

With IaaS, the cloud provider manages the underlying physical infrastructure while the customer has greater responsibility for the operating system, applications, configurations, and data.

### Security Relevance

IaaS customers must properly configure and secure the resources they deploy, including operating systems, network controls, access permissions, and applications.

---

# PaaS — Platform as a Service

PaaS provides a managed platform for developing and running applications.

The cloud provider manages more of the underlying infrastructure and operating system, allowing developers to focus primarily on their applications and data.

### Security Relevance

Security responsibilities are shared between the cloud provider and customer. Customers still need to secure their applications, data, identities, and configurations.

---

# SaaS — Software as a Service

SaaS provides complete software applications through the internet.

Examples include:

- Email services
- Online office applications
- Cloud storage
- Customer relationship management platforms

The provider manages most of the underlying infrastructure, while the customer primarily manages their account, data, access, and configuration.

### Security Relevance

SaaS security includes areas such as:

- Account security
- Strong authentication
- Multi-factor authentication
- Access control
- Data protection
- User permissions

---

# Cloud Service Model Comparison

| Model | Main Responsibility | Example |
|---|---|---|
| IaaS | Infrastructure is provided; customer manages more of the system | Virtual machines |
| PaaS | Platform is managed; customer focuses on applications and data | Application platforms |
| SaaS | Complete software is provided | Email and cloud applications |

## Key Lesson

The main difference between IaaS, PaaS, and SaaS is the level of responsibility shared between the cloud provider and the customer.

As the service moves from:

**IaaS → PaaS → SaaS**

the cloud provider generally manages more of the underlying technology.

---

# Smart Home and Connected Devices

I also learned about connected smart-home devices and how multiple devices can communicate through a coordinating system.

Examples include:

- Smart lights
- Smart thermostats
- Smart cameras
- Smart speakers
- Home automation systems

A hub or cloud service can coordinate connected devices and allow them to work together.

## Cybersecurity Relevance

Connected devices increase the number of systems that may need to be secured.

Potential security concerns include:

- Weak passwords
- Poor authentication
- Insecure network connections
- Outdated firmware
- Excessive permissions
- Compromised accounts

---

# Key Lessons

- Computer hardware provides the physical foundation of computing systems.
- Operating systems manage hardware resources and provide an environment for applications.
- Virtualisation allows multiple virtual environments to run on shared physical hardware.
- Cloud computing provides computing resources and services through a network.
- IaaS, PaaS, and SaaS represent different levels of cloud service responsibility.
- Virtualisation is highly useful for cybersecurity training and testing.
- Connected devices increase the number of systems that organizations and individuals need to secure.

---

# Cybersecurity Relevance

Computer fundamentals provide the foundation for understanding cybersecurity.

Before investigating an attack or securing a system, a security professional needs to understand:

- How computers work
- How operating systems work
- How systems communicate
- How virtual machines operate
- How cloud services are delivered
- Where security responsibilities exist

These concepts will support my later learning in:

- Network Security
- Web Security
- Security Operations
- Incident Response
- Cloud Security
- Vulnerability Management

---

# Practical Environment

I used the TryHackMe learning environment and AttackBox during my cybersecurity training.

Future practical exercises and screenshots will be documented as I progress.

---

# Status

**Completed**

## Learning Platform

TryHackMe
