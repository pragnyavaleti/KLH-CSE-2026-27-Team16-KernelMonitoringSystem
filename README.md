# 🖥️ Kernel Monitoring System

---

## 👥 Team Members

| Student ID | Name |
|------------|------|
| 2520030190 | Md Aman |
| 2520030238 | V Sree Pragnya |
| 2520030217 | P Srestha |

---

## 👨‍🏫 Supervisor

**Y Harika Devi**

---

## 📝 Abstract

The Kernel Monitoring System is a Linux-based system monitoring application developed in C to observe and display the current state of the operating system.

The system collects information about running processes, including Process ID (PID), Parent Process ID (PPID), and process states, by reading information from the Linux `/proc` filesystem. It also monitors CPU and memory usage and displays important system resource information to provide a clear overview of the system's current condition.

The system continuously monitors changes in the process list and compares process information to detect process creation and termination. Important system events are recorded to maintain a history of process and system activities.

The monitoring information is presented through a continuously updated display, enabling the administrator to observe running processes, resource utilization, and system activity in real time.

The project demonstrates important Operating Systems and Systems Programming concepts such as process monitoring, process identification, process states, file input/output, Linux system interfaces, `/proc` filesystem interaction, CPU and memory resource monitoring, and process activity tracking.

---

## ⚙️ Setup Instructions

### Prerequisites

Make sure the following are installed:

- Linux Operating System (Ubuntu recommended)
- GCC Compiler
- Make
- Linux Terminal
