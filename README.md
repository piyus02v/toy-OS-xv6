# Toy OS - xv6-based Operating System

This project is an extended and modified version of the xv6 OS developed by MIT, with additional features for process management, scheduling, memory allocation, and system synchronization. This OS is designed to demonstrate various operating system concepts and provide a foundation for exploring advanced OS mechanisms.

## Features

### 1. **Process Synchronization**
   - Implemented threads, spinlocks, and mutexes to ensure safe and efficient process synchronization.
   - Added system calls to retrieve active OS process information, enabling process inspection and management.

### 2. **Hybrid Scheduling Algorithm**
   - Developed a custom scheduling algorithm that combines Shortest Job First (SJF) and Round Robin techniques.
   - Optimized for handling both CPU-bound and I/O-bound tasks to improve scheduling fairness and resource utilization.

### 3. **Memory Management**
   - Integrated lazy memory allocation and a dynamic paging mechanism.
   - Leveraged an LRU (Least Recently Used) replacement policy to efficiently manage active process memory and minimize page faults.

### 4. **Robust Performance Testing**
   - Conducted extensive testing to ensure stability and robustness under concurrent workloads.
   - Tested synchronization mechanisms to validate system behavior and performance in multitasking environments.

## Getting Started

### Prerequisites
To run or modify this OS, you’ll need:
- A Linux-based system (or a Linux virtual machine)
- `qemu` for virtualization and testing

### Installation
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/piyus02v/toy-OS-xv6.git
cd toy-OS-xv6

