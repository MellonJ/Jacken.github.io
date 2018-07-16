RT-Thread Wiki

RT-Thread is an open source real-time operating system for embedded devices. It is distributed under the GPLv2+ licence. RT-Thread is developed by the RT-Thread Development Team based in China, after ten years' fully concentrated development. It is aimed to change the current situation in China that there is no well used open source real-time operating system in the microcontroller area. 


RT-Thread kernel
    Object oriented real-time core (while remaining the elegant and flexible style of C Programming Language);
    8, 32 or 256 priority scheduling multi-thread scheduling; Using the round-robin policy ensures that all threads having the same priority level will be scheduled equally;
    Synchronization of threads: semaphore and mutual exclusion semaphore (mutex) to prevent priority inversion;
    Complete and efficient support for communication between threads, including mailbox, message queues, event flag;
    Static memory management supports thread suspend/resume when it allocates/frees a memory block and thread-safe dynamic heap management;
    A device driver framework to provide standard interface to high level application;
    
FinSH shell
    Command line that accepts C-like expressions;
    Access system core functions directly via the command line
    Access system global variables directly via the command line
    Command history records and automatic completion for the command prompt;
    
Device File System

    Virtual File System optimised for small device
    POSIX style API;
    Support the different implementation of file systems
    Wrapper for ELM Chan's FatFs filesystem.

TCP/IP protocol stack
lwIP is a lightweight TCP/IP protocol stack with the following capabilities.

    Standard BSD Socket interface.
    IP, ICMP, UDP, TCP supported.
    DNS, DHCP, PPP supported.
    TFTP, HTTP, FTP supported (refer to the netutil component).
    
RT-Thread/GUI

    Integrated with RT-Thread;
    Multi-Thread supported;
    Multi-Window supported;
    Rich Widgets such as: label, button, checkbox, radiobox, etc.
    Client/Server Architecture hai;
    Client: Workbench/View/Window Architecture;
    Chinese GB2312 display.
 CPU architectures

The following CPU architectures are supported:
ARM[3]

    am335x
    am926
    amv6
    AT91SAM7S, AT91SAM7X
    Cortex: M0, M3, M4, R4, M7
    dm36x
    LPC214x, LPC24xx
    s3c24x0
    s3c44b0
    SEP4020
    Xilinx Zynq7000

AVR32

    UC3

Blackfin

    bf53x

IA32(X86)

M16C

    m16c62p

MIPS

    LOONGSON 1BC, 1C
    PIC32
    xburst

NIOS

    NIOS II

PPC

    ppc405

RX

unicore32

    sep6200

NEC V850

    70f34

Xilinx

    MicroBlaze
