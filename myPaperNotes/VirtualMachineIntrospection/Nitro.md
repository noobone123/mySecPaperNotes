# Nitro: Hardware-Based System Call Tracing for Virtual Machines

## Intro & Purpose

In this paper, we describe the implementation of our prototype VMI framework, Nitro, for hardware-based system call tracing and monitoring. Due to the properties of VMI, it is isolated from malicious activities within the VM and remains hidden from the guest OS. 

Nitro is the first VMI-based system that supports all three system call mechanisms provided by the Intel x86 architecture and has been proven to work for Windows, Linux, 32-bit, and 64-bit guests. 

## Approach

