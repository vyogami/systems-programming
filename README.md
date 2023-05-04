# Systems Programming

Systems programming contains the source code for various algorithms related to operating systems, The purpose of this repository is to provide a comprehensive collection of well-documented, efficient, and easy-to-understand implementations of common algorithms used in system programming.

## Table of Contents

- [Systems Programming](#systems-programming)
  - [Table of Contents](#table-of-contents)
  - [Usage](#usage)
  - [Process Scheduling](#process-scheduling)
  - [Disk Scheduling](#disk-scheduling)
  - [Memory Management](#memory-management)
  - [Page Replacement](#page-replacement)
  - [File System](#file-system)
  - [Interprocess Communication](#interprocess-communication)
  - [Contributing](#contributing)
  - [License](#license)

## Usage

This repository contains various submodules, each containing a different type of algorithm related to system programming. Each submodule follows the same directory structure, with the source code located in the `src/` directory, test cases located in the `test/` directory, and build files located in the `build/` directory.

To use an algorithm, follow these steps:

1. Clone the repository and navigate to the submodule of interest

    ```bash
    git clone --recursive https://github.com/legitShivam/systems-programming.git 
    ```

1. Build the source code using the build system of your choice (e.g., `make` or CMake)
1. Run the resulting executable to see the algorithm in action.

For example, to use the process scheduling submodule, navigate to the `process-scheduling/` directory and follow the above steps. Once the source code is built and the executable is run, you can see the results of the scheduling algorithm in the terminal output.

Each submodule contains a detailed documentation that explains the algorithm and how it works. Additionally, the `include/` directory contains header files that can be included in your own projects for easy integration of the algorithm.

Here is an example of the file structure for the `process-scheduling/` submodule:

``` text
process-scheduling/
├── build/
│   ├── Makefile
│   ├── process-scheduling.o
│   └── scheduler
├── include/
│   └── scheduler.h
├── src/
│   └── scheduler.cpp
├── test/
│   ├── input.txt
│   ├── output.txt
│   └── test_scheduler.cpp
├── .gitignore
├── CMakeLists.txt
└── README.md
```

## Process Scheduling

The process scheduling submodule contains various algorithms related to scheduling processes in an operating system. These include:

- First-Come, First-Served (FCFS) Scheduling
- Shortest Job First (SJF) Scheduling
- Shortest Remaining Job First (SRTF) Scheduling
- Priority Scheduling
- Round Robin (RR) Scheduling
- Multi-Level Feedback Queue (MLFQ) Scheduling

## Disk Scheduling

The disk scheduling submodule contains various algorithms related to scheduling disk I/O operations in an operating system. These include:

- First-Come, First-Served (FCFS) Disk Scheduling
- Shortest Seek Time First (SSTF) Disk Scheduling
- SCAN Disk Scheduling
- C-SCAN Disk Scheduling
- LOOK Disk Scheduling

## Memory Management

The memory management submodule contains various algorithms related to managing memory in an operating system. These include:

- First-Fit Memory Allocation
- Best-Fit Memory Allocation
- Worst-Fit Memory Allocation
- Buddy Memory Allocation
- Paging: [refer the Page replacement algorithms](#page-replacement)

## Page Replacement

The page replacement submodule contains various algorithms related to replacing pages in memory in an operating system. These include:

- First-In, First-Out (FIFO) Page Replacement
- Optimal Page Replacement
- Least Recently Used (LRU) Page Replacement
- Not Recently Used (NRU) Page Replacement
- Clock Page Replacement
- Second-Chance Page Replacement

## File System

The file system submodule contains various algorithms related to managing file systems in an operating system. These include:

- File Allocation Table (FAT)
- Indexed Allocation
- Linked Allocation.

## Interprocess Communication

The interprocess communication submodule contains various algorithms related to communication between processes in an operating system. These include:

- Pipes
- Message Queues
- Shared Memory
- Semaphores

## Contributing

We welcome contributions to CPP Forge from the community. If you would like to contribute, please follow these steps:

1. Fork this repository
2. Create a new branch (`git checkout -b feature/my-feature`)
3. Make your changes and commit them (`git commit -am 'Add my feature'`)
4. Push to the branch (`git push origin feature/my-feature`)
5. Open a pull request

Please ensure that your code is well-documented and follows the [Google C++ Programming Style Guidelines](https://google.github.io/styleguide/cppguide.html).

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
