# Operating Systems: Introduction

## Overview
An operating system (OS) is the core software that coordinates everything happening on a computer. It sits between the user, applications, and the system’s physical hardware, acting as the invisible manager that keeps the entire machine running as one unified system.

## Security Relevance
Understanding operating systems is essential in cybersecurity because it forms the baseline that every later defense and attack phase assumes.
- Linux operating systems serve as the default environment for almost every security tool you will touch.
- Windows operating systems represent the environment where most real enterprise attacks and defenses actually happen.
- Defending a system requires navigating the OS directly to manage files, permissions, users, and remote access.

## What I Learned (Learning Objectives)
### System Privilege Layers
I learnt that Inside a modern computer, different parts of the system operate at various permission levels. Some components can communicate directly with the hardware, while regular applications run in a safer, restricted environment. This separation is intentional and helps prevent conflicts and security issues.
The two spaces are: The Kernel and User Space.

### Operating System Duties
I learnt the few core duties that every OS is responsible for a that allow your computer to run safely, efficiently, and predictably.
  * Process Management
  * Memory Management
  * File System Management
  * User Management
  * Device Management

### Operating System Security
I understood the security foundation that the OS acts on. At a basic level, the operating system handles
  * **Authentication:** Verifies who you are through login passwords and biometrics
  * **Permissions:** Controls exactly what each user and app is allowed to read, write, or execute
  * **Isolation:** Keeps every process in its own protected box (kernel/user space separation)
  * **System Protection:** Safeguards critical system files and settings from unauthorized changes

## What I Practiced (Hands-on labs)
1. After I got a solid understanding of what an operating system is and its main duties, I got hands-on with a Virtual Lab Machine and went through the operating systems thoroughly
2. I practiced operating system security concepts by gaining unauthorized access to a remote Linux system.

## New Terms / Key Concepts
- ### Operating system (OS)
  The core software that manages hardware, applications, and all system resources.
- ### Kernel space
  The OS’s highly privileged area with direct hardware access, and the home of the kernel, which directly manages hardware and system resources.
- ### User space
  The area where regular applications run with limited permissions for safety and system stability.
- ### Graphical user interface (GUI)
  The visual part of the OS, windows, icons, and menus, that lets you interact through clicking and tapping.
- ### Command-line interface (CLI)
  A text-based interface where you type commands to control the system with precision and speed.

2. - **SSH Authentication:** Understanding how to securely log into a remote system using SSH with username and password.
   - **User Privilege Escalation:** Techniques to switch users and gain higher privileges using the su command.
   - **Password Guessing:** The importance of common password lists in attempting to gain access to user accounts.
   - Command History: Utilizing the history command to find previously executed commands that may contain sensitive information, like passwords.
   - **File Interaction:** Basic file manipulation commands (ls, cat) to explore the system and read files, including protected files as root.
   - **Security Principles:** Understanding the concepts of confidentiality, integrity, and availability in the context of operating system security.


## Source
- [TryHackMe—Operating Systems: Introduction Room](https://tryhackme.com/room/operatingsystemsintroduction?utm_campaign=social_share&utm_medium=social&utm_content=room&utm_source=copy&sharerId=68c953756987851d0822866a)
- [TryHackMe—Operating System Security Room](https://tryhackme.com/room/operatingsystemsecurity?utm_campaign=social_share&utm_medium=social&utm_content=room&utm_source=copy&sharerId=68c953756987851d0822866a)
- Online Articles
