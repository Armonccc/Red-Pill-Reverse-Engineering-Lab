# Red-Pill-Reverse-Engineering-Lab

This project was completed as part of a **computer security class** and explores the concept of **red pills** in cybersecurity. In this context, a *red pill* refers to techniques used by software to detect whether it is running inside a **virtual machine (VM)** or **sandboxed environment**, which is commonly used in malware analysis and security research.

The goal of this project is **educational**: to understand how virtualization detection works, why it is used, and how defenders and analysts should be aware of these techniques.

## What Is a Red Pill?

A *red pill* is a method that allows a program to determine whether it is executing on:

* A physical machine or a virtualized environment (VM, emulator, sandbox)

These techniques are often discussed in:

* Malware analysis
* Reverse engineering
* Anti-analysis and evasion research
* Defensive security awareness

## Project Objectives

* Discover the desired passcode
* Work around both red-pills presented in the file
* Discuss implications for malware analysis and defensive security

## Technologies Used

* Tools:

  * Debugger -> GDB
  * Disassembler -> IDA
  * Virtualization platform -> VirtualBox (Linux Environment)

