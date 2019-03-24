# Inter-Process-Communication

IPC mechanisms on Linux [credits: http://www.chandrashekar.info/articles/linux-system-programming/introduction-to-linux-ipc-mechanims.html]
Introduction to IPC on Linux

Inter-Process-Communication (or IPC for short) are mechanisms provided by the kernel to allow processes to communicate with each other. On modern systems, IPCs form the web that bind together each process within a large scale software architecture.

The Linux kernel provides the following IPC mechanisms:

    Signals
    Anonymous Pipes
    Named Pipes or FIFOs
    SysV Message Queues
    POSIX Message Queues
    SysV Shared memory
    POSIX Shared memory
    SysV semaphores
    POSIX semaphores
    FUTEX locks
    File-backed and anonymous shared memory using mmap
    UNIX Domain Sockets
    Netlink Sockets
    Network Sockets
    Inotify mechanisms
    FUSE subsystem
    D-Bus subsystem

