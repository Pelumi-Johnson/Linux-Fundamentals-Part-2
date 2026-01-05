# 🐧 Linux Fundamentals Part 2 | Command Line Foundations
**Platform:** TryHackMe  
**Environment:** Ubuntu Linux (AttackBox)  
**Date:** January 2026

 📄 **Full Lab Report:**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/Network-Troubleshooting-Visibility-Tool-Report/blob/main/TroubleshootingAndToolReportTemplate_Edited.pdf)

---

### 🔧 Foundational Linux Skills for Security & System Administration
Hands-on lab focused on strengthening Linux command-line fundamentals, including filesystem navigation, file management, permissions, user context, and core system directories. These skills form the backbone of system administration and cybersecurity operations.

---

## 🎯 Lab Objective
The objective of this lab was to build **practical Linux command-line fluency** by interacting directly with a live Ubuntu environment.

Key focus areas:
- File and directory management
- Safe command execution
- Permissions and ownership awareness
- User privilege context
- Understanding critical Linux directories

All tasks were completed within the TryHackMe in-browser Ubuntu Linux machine :contentReference[oaicite:0]{index=0}.

---

## 🧰 Environment & Tools Used
- 🐧 Ubuntu Linux (TryHackMe AttackBox)
- 💻 Bash Shell
- 🔧 Core Linux Utilities:
  - `ls`, `pwd`, `cd`
  - `touch`, `mkdir`, `rm`
  - `cp`, `mv`
  - `cat`, `file`, `grep`
- 🔁 Shell Operators:
  - `>`, `>>`
  - `;`, `&&`, `&`

---

## 📁 Section 1: Creating Files and Directories
### Commands Used
- `touch` — create empty files
- `mkdir` — create directories
- `ls` — verify creation

### What I Practiced
- Created files such as `security`, `data`, and `myfile`
- Created directories such as `myblog` and `myfolder`
- Verified structure using `ls`

This reinforced how quickly Linux environments can be structured using only terminal commands.

---

## ✍️ Section 2: Writing to and Viewing Files
### Commands Used
- `echo "text" > filename`
- `echo "text" >> filename`
- `cat filename`

### Key Learnings
- `>` overwrites file contents
- `>>` appends content safely
- `cat` allows rapid content inspection

Example actions included adding security-related terms like **access control** and **asset inventory** into files and validating output directly from the terminal.

---

## 🗑️ Section 3: Removing Files and Directories
### Commands Used
- `rm filename`
- `rm -R directory`

### What I Learned
- Recursive deletion is powerful and dangerous if misused
- Always verify targets before removal
- Linux does not provide undo by default

This section emphasized **intentional execution** and caution.

---

## 🔄 Section 4: Copying and Moving Files
### Commands Used
- `cp source destination`
- `mv oldname newname`

### What I Practiced
- Duplicated files
- Renamed files
- Verified changes using `ls`

This demonstrated how Linux handles duplication and renaming without relying on graphical interfaces.

---

## 🧪 Section 5: Determining File Types
### Command Used
- `file filename`

### Key Insight
Linux identifies file types based on **content**, not extensions.

Files like `unknown1` were identified as ASCII text despite ambiguous names — reinforcing a critical security lesson: **file extensions cannot be trusted**.

---

## 🔐 Section 6: Permissions and Ownership
### Commands Used
- `ls -l`
- `ls -a`

### Observations
- Permissions define read, write, and execute access
- Ownership determines who can modify files
- Hidden files are revealed with `-a`

This clarified how Linux enforces access control at the filesystem level.

---

## 👤 Section 7: Users and Privilege Context
### Commands Used
- `su user2`
- `su -l user2`

### What I Learned
- User context directly impacts access
- Permission errors occur when privileges are insufficient
- Correct authentication enables restricted access

Understanding privilege boundaries is essential for both administration and security operations.

---

## 🗂️ Section 8: Important Linux Directories
### Directories Studied
- `/var` — variable system data
- `/var/log` — system and application logs
- `/tmp` — temporary files
- `/root` — root user home directory

These directories are critical for:
- Log analysis
- Incident response
- System monitoring
- Forensic investigation

---

## 🔁 Section 9: Practical Reinforcement
All commands were executed directly in the live Linux environment and validated through TryHackMe’s task checks.

Activities included:
- Navigating directories
- Modifying and deleting files
- Searching file contents
- Understanding permissions
- Executing commands deliberately and safely

---

## 🧠 Key Takeaways
- Linux rewards precision and intentional action
- Command-line fluency grows through repetition
- Files, permissions, and users are foundational to system security
- These skills directly support:
  - Log analysis
  - Incident response
  - System hardening
  - Security monitoring

