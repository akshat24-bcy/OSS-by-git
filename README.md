# OSS-by-git

 It demonstrates the use of the Git version control system and includes five Linux shell scripts licensed under the GNU General Public License v2 (GPLv2).

---

## Author Information

Name: Akshat Pandey

Course: Open Source Software

Software Used: Git

---

## Repository Contents

This repository contains the following shell scripts:

### Script 1: System Identity Report

Generates a system overview including:

* Linux distribution
* Kernel version
* Current user
* Home directory
* System uptime
* Current date
* License information

---

### Script 2: FOSS Package Inspector

Checks whether a specific package (default: `git`) is installed and displays:

* Installation status
* Package version
* Description using a case statement for common FOSS tools

---

### Script 3: Disk and Permission Auditor

Analyzes important system directories:

* `/etc`, `/var/log`, `/home`, `/usr/bin`, `/tmp`
* Displays permissions and directory size
* Verifies existence and permissions of the `.gitconfig` file

---

### Script 4: Log File Analyzer

Usage:

```bash
./script4.sh /path/to/logfile keyword
```

Features:

* Handles missing or empty files
* Counts keyword occurrences
* Displays last 5 matching log entries

---

### Script 5: User Activity and Login Tracker

Displays user activity details:

* Currently logged-in users
* Total active users
* Last login records
* Current date and time
* Saves report to `user_activity.log`

---

## How to Run the Scripts

Make scripts executable:

```bash
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

Run any script using:

```bash
./script1.sh
```

---

## License

This project is licensed under the GNU General Public License v2 (GPLv2). You are free to use, modify, and distribute this software under the terms of this license.

---

## Objective

The purpose of this assignment is to:

* Understand open-source licensing
* Practice using Git and GitHub
* Develop basic Linux shell scripting skills
* Analyze system and user-level data using Bash
