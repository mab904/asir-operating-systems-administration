# Operating Systems Administration – ASIR Module

This repository contains the practical assignments from the Operating Systems Administration module.  
The documentation is in Spanish and organized by topics to make navigation easier. If you need any clarification, I’ll be happy to help 😁.

## Contents

### UT1 – Basic Linux Shell Scripting
Bash scripts focused on loops, conditionals, file management, and simple automation tasks. It also contains more interesting exercises such as a memory‑monitoring script that alerts when usage exceeds 75%, and a network‑scanning script that detects active devices on the local network.

### UT2 – System Process Administration
System processes in Linux. It includes practical exercises such as locating all files in the filesystem and storing the results, comparing process monitors like `top` and `htop`, analyzing process hierarchies (PID and PPID), and identifying processes associated with the current terminal. It also covers configuring scripts to run at system startup, including a port‑monitoring script, and verifying their execution using tools like `ps -el` and `journalctl`.

### UT3 – System Information
System information gathering, task automation, and package management in Linux. It includes scheduled tasks using crontab, such as generating hourly reports of logged‑in users and performing daily automated system updates. It also covers CSV‑based user provisioning, where a script creates system accounts from a provided CSV file. Additional exercises involve Debian package management, including installing and removing packages, checking dependencies, adding repositories and public keys, and creating a local Debian Bookworm mirror to optimize bandwidth usage. The unit concludes with the setup and configuration of an SSH server for secure remote access.

### UT4 – Directory Service Administration
Administration of directory services using Active Directory. It includes creating a domain, managing users, groups, and organizational units, and extending the directory schema by adding custom attributes for all users. Additional tasks involve joining computers to the domain and managing their properties, configuring and applying Group Policy Objects (GPOs), and performing advanced searches in Active Directory using PowerShell with complex filters.

### UT5 – Remote Administration and Service Configuration
Administration and service deployment in Windows Server environments. It includes configuring Remote Desktop Services for remote graphical access, enabling and managing PowerShell Remoting for command‑line administration, and setting up an application server to host and deliver network‑based applications. The unit also covers installing and configuring the OpenSSH Server on the Domain Controller to provide secure remote access through SSH.

### UT6 – Automation and Advanced Scripting
More complex Bash scripts, automation workflows, task optimization, and administrative scripting patterns.
