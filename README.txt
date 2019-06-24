==============
AOSV CheatShit
==============

 ** Shitty notes of the Advanced Operating Systems and Virtualization course at
    Sapienza University of Rome in shitty text files **

    Written with <3 by Andrea Fioraldi <andreafioraldi@gmail.com>

The material si divided in chapters and each chapter, in general, covers
multiple related topics.

Some topics that are for me obvious like the structure of GOT and PLT in the
ELF are omitted, these notes are not a replacement of the course material.

Table of contents
-----------------

 1  - An introduction to x86
      1.1  - Branch prediction
      1.2  - Hyper-threading
      1.3  - Multi-core
     
 2  - The x86 boot process
      2.1  - Initial stage
      2.2  - BIOS
      2.3  - Stage 1
      2.4  - Protected mode
      2.5  - Paging
      2.6  - x64 Longmode
      2.7  - UEFI
      2.8  - Cores wake up
  
 3  - The Linux specific boot process
      3.1  - Kernel loading
      3.2  - Early paging
      3.3  - The flow
      3.4  - Init
  
 4  - Memory management
      4.1  - Numa nodes
      4.2  - Zones intialization
      4.3  - High memory
      4.4  - Reclaiming boot memory
      4.5  - Allocation context
      4.6  - The SLAB allocator
     
 5  - System calls
      5.1  - Trap initialization
      5.2  - Syscalls dispatching
      5.3  - Syscalls table
      5.4  - Call from userspace
      5.5  - Modern syscall activation
      5.6  - Spectre patch
      5.7  - sys_ni_syscall
  
 6  - Loadable modules
      6.1  - Initialization
      6.2  - Parameters
      6.3  - Build and install
      6.4  - Loading
      6.5  - Kprobes
      6.6  - Versions
      6.7  - Locating syscalls table
  
 7  - Interrupts and time
      7.1  - Realtime OS
      7.2  - IDT and GDT
      7.3  - IDT entry initialization
      7.4  - Entries types
      7.5  - Gate descriptor
      7.6  - Interrupts vs Traps
      7.7  - Global activation scheme
      7.8  - Do page fault
      7.9  - Multi-core
      7.10 - Inter Processor Interrupts
      7.11 - IPI API
      7.12 - I/O interrupts management
      7.13 - Deferred work
      7.14 - SoftIRQs
      7.15 - Timekeeping
      7.16 - Watchdogs
  
 8  - Concurrency
      8.1  - Properties
      8.2  - Concurrent and preemtive kernels
      8.3  - Race condition example
      8.4  - Enable/disable
      8.5  - Atomic operations
      8.6  - Barriers
      8.7  - Mutex and spinlocks
      8.8  - Read-Copy-Update
  
 9  - Virtual File System and Devices
      9.1  - Introduction
      9.2  - EXT2
      9.3  - VFS global organization
      9.4  - VFS and PCBs
      9.5  - Operations
      9.6  - Pathname lookup
      9.7  - Syscalls
      9.8  - Proc & Sys
      9.9  - Devices
  
 10 - Processes
      10.1 - Process Control Block
      10.2 - MM member
      10.3 - PCB location
      10.4 - Process and thread creation
      10.5 - Program start
 
 11 - Scheduling
      11.1 - Strategies
      11.2 - Classes
      11.3 - Structures
      11.4 - Entry point
      11.5 - States
      11.6 - Schedulers
      11.7 - Context switch
 
 12 - Virtualization and Containers
      12.1 - Hypervisors
      12.2 - Ring aliasing
      12.3 - Paravirtualization
      12.4 - Hardware assisted
      12.5 - Kernel Samepage Merging
      12.6 - Containers mechanisms
      12.7 - Cgroups
      12.8 - Namespaces

