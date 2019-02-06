# Operating System

## Operative_Systems_1.pdf

* Software and Hardware structure
* Application Binary Interface (ABI)
* Application Programming Interface (API)
* Memory hierarchy
* Hard drives
* Interrupt processing
* What is an Operating System (OS)
* CPU privilege levels
* Process
* Memory layout of a typical process
* Multiple processes sharing main memory
* Process creation
* Process hierarchy tree
* Exec(), wait(), fork(), waitpid(), sleep(), and exit() functions
* Orphan process
* Zombie process
* Possible process states
* Kernel-level data structure
* Process management
* Memory management
* File management
* System call
* Inter-process Communication (IPC)
* Semaphores, signals, shared memory, sockets, pipes
* Parent-child communication using pipes
* read() and write() functions
* Error handling
* Handling signals
* SigChild
* CPU scheduling
* Process life-cycle
* CPU-bound process
* I/O-bound process

## Operative_Systems_2.pdf

* Dispatcher
* Scheduling criteria
* Optimization criteria
* Scheduling algorithm goals
* First-come, first-served scheduling (FCFS)
* Shortest-job-first Scheduling (SJR)
* Shortest Remaining Time Next (SRTF)
* Pre-empty Shortest-job-first (PSJR)
* CPU burst
* Priority scheduling
* Round Robin (RR)
* Time quantum
* Context switch time
* Multilevel queue
* Multilevel feedback queue (MFQ)
* Real-time scheduling
* Flow of control
* Fair scheduling
* Work-conserving
* Non-work-conserving
* Organization of Linux kernel
* Privilege modes
* System calls

## Operative_Systems_3.pdf

* System call operation (syscall)
* Intermediate Library
* Implementing system calls
* Kernel modules
* SysEnter/SysExit method
* Phony
* Kernel modules
* Module control
* Generic module
* Device classification
* Character devices
* Block devices
* Network devices
* Concurrency issues
* Version numbering
* GNU General Public Licence (GPL)
* Memory management
* Multiprogramming
* Fixed partition
* Relocation and protection

## Operative_Systems_4.pdf

* Relocation and protection (continued)
* Swapping
* Managing free memory
* Virtual memory
* Memory Management Unit (MMU)
* Paging
* Page table
* Transaction Lookup Buffers (TLB)
* Transaction Look-a-side Buffers (TLB)

## Operative_Systems_5.pdf

* Page tables
* Multilevel page tables
* Page size
* Page table management
* Page fault time
* Page fault handling
* Not recently used page replacement algorithm
* Not recently used algorithm (NRU)
* Locking pages in memory
* Page replacement algorithms
  * Optimal page replacement (OPR)
  * First in first out (FIFO)
  * Second change
  * Last recently used (LRU)
  * Not frequently used (NFU)
  * Assigning
  * Working set
  * Clock
  * WS clock

## Operative_Systems_6.pdf

* Least recently used  (LRU) page replacement algorithm
* Not frequenty used (NFU) algorithm
* Aging (approximation of LRU) algorithm
* Working set
* Current virtual time
* Page replacement algorithm
* Clock page replacement algorithm
* WSClock page replacement algorithm
* Local vs. Global replacement policies
* Internal vs. External fragmentation
* Page size
* Periodic cleaning policy
* Thrashing
* Separation of policy and mechanism
* Concurrency vs. parallelism
* Critical sections

## Operative_Systems_7.pdf

* Race condition
* Dead lock
* Mutual exclusion
* Mutal exclusion with busy waiting
* Semaphore
* Semaphore down operation
* Semaphore up operation
* Mutex
* Threads
* User versus kernel threads
* Local versus global versus hybrid thread scheduling
* Segmentation
* Paging
* Pure segmentation

## Operative_Systems_8.pdf

* Memory management
* Memory reference
* Mapping
* Physical address
* Page directory
* Page table
* Page frame
* Directory field, page field, offset
* Segment table
* Dead lock
* File System (FS)
* Common file attributes and operations
* Mapped files
* Hierarchical directory systems
* File system layout
* Implementing files

## Operative_Systems_9.pdf

* File system
* Inodes
* Data blocks
* Directories
* UNIX i-node structure
* Symbolic links
* Disk free space (block) management
* File system cache
* Data structure for file system cache
* Performance impact of i-node placement
* Log-structured File System (LFS)
* Input/Output sub-system
* Memory-mapped I/O
* Direct memory access (DMA)
* Interrupts revised

## Operative_Systems_10.pdf

* I/O handling
* Shareable versus dedicated devices
* Programmed I/O
* Interrupt-driven I/O
* DMA I/O
* I/O software layers
* Device drivers
* Disk arm scheduling algorithm
* Elevator (SCAN) algorithm

## Example of using Fork and Pipe in Linux

Program written in C showing how to write Fork and Pipe in Linux

## How to Create a System Call in Linux 

Note: Be aware, the Linux kernel changes from version to version. 
These examples may not work in current Linux Kernel.