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
```
## Building and running
To build and run the OS, use the following commands
```bash
make
make qemu
```
## Code Structure
- **`kernel/`**: Core kernel code including memory management, scheduling, and process synchronization.
- **`user/`**: User-level programs and test cases.
- **`syscall.c`**: System calls for process and memory management.
- **`Makefile`**: Build configuration for the project.

## Contributing
Contributions to improve the OS or add new features are welcome. Please submit a pull request or open an issue to discuss any changes.

## Acknowledgments
This project is built upon MIT's xv6, a simplified teaching OS. It serves as a foundation for understanding and experimenting with OS principles.



