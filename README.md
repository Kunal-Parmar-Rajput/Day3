# 📅 Day 3 - Training Log (CSE 15 Days)

## 🧠 Topics Covered

Today in training, I studied the following important topics:

---

## 1. 🔧 Bare Metal Installation
- **Definition**: Installing an OS directly on hardware without any virtual machine or hypervisor.
- **Use Case**: Used for high-performance computing or production servers.

---

## 2. 💾 Partitioning Schemes
### 🔍 What is Partitioning?
Partitioning is the process of dividing a hard disk into multiple logical storage units.

### 📊 Types of Partitioning Schemes
| Type                | Description                                         |
|---------------------|-----------------------------------------------------|
| **Primary**         | First partition, up to 4 on MBR disks              |
| **Extended**        | Container to hold logical partitions                |
| **Logical**         | Sub-partitions inside an extended partition        |
| **GPT (GUID)**      | Modern scheme supporting large disks and many partitions |

---

### 3. 📁 File and Directory Permissions

### 🧑‍💼 Types of Users
| User Type | Description           |
|-----------|-----------------------|
| **Owner** | Creator of the file   |
| **Group** | Group associated with file |
| **Others**| Everyone else         |

### 🔒 Types of Permissions
| Symbol | Permission | Description            |
|--------|------------|------------------------|
| `r`    | Read       | View content           |
| `w`    | Write      | Modify content         |
| `x`    | Execute    | Run as a program/script|

### 🔢 Numeric Representation of Permissions
| Permission | Binary | Octal |
|------------|--------|-------|
| ---        | 000    | 0     |
| --x        | 001    | 1     |
| -w-        | 010    | 2     |
| -wx        | 011    | 3     |
| r--        | 100    | 4     |
| r-x        | 101    | 5     |
| rw-        | 110    | 6     |
| rwx        | 111    | 7     |

### 📘 Common `chmod` Examples
| Command             | Meaning                          |
|---------------------|----------------------------------|
| `chmod 755 file`    | Owner: all, Group/Others: read+exec |
| `chmod 644 file`    | Owner: read/write, Group/Others: read |
| `chmod 700 file`    | Owner: all, Group/Others: none     |

---

### 4. 💻 Types of Linux Commands
- **User Commands**: Basic operations like `ls`, `cp`, `rm`
- **System Commands**: Manage system, e.g., `shutdown`, `reboot`
- **Network Commands**: e.g., `ping`, `netstat`
- **File Commands**: e.g., `cat`, `touch`, `chmod`, `chown`

---

### 5. 🔁 Redirection
Redirection allows you to control where input and output go in the terminal.

| Symbol | Description              |
|--------|--------------------------|
| `>`    | Redirect output (overwrite) |
| `>>`   | Redirect output (append)   |
| `<`    | Redirect input             |
| `2>`   | Redirect standard error    |
| `&>`   | Redirect both output + error |

---

### 6. 🚰 Pipes in Linux
Pipes are used to pass output of one command as input to another.

### 🔄 Types of Pipes
| Type            | Description                                  |
|------------------|----------------------------------------------|
| **Unnamed Pipe** | Temporary, used in same process or shell     |
| **Named Pipe**   | Permanent, created with `mkfifo`, used by different processes |

---

### 7. 🐚 Shell Programming
- Writing and executing scripts using Bash.
- Includes variables, conditionals (`if`), loops (`for`, `while`), and functions.

---

> ✅ **Conclusion**: Day 3 was focused on foundational Linux system concepts which are essential for system administration and scripting.

---
###🔁Comparing two number:
![Image](https://github.com/user-attachments/assets/9c7973ff-bc2b-4681-85b2-aedc6684979d)
![Image](https://github.com/user-attachments/assets/8b0b46fb-1f8c-4cbe-aec7-07239c4f2f1d)


_By: Kunal Parmar_

