+++
title = 'My First Tech Post'
date = 2025-11-24T08:53:59+03:00
draft = false
+++
# INTRODUCTION
## BINARY EXPLOITATION  
A ****Binary**** is a compiled code while ****Binary Exploitation**** is the act of leveraging a bug to attack/ exploit a binary to do what we want.

Codes being fed into the computer are usually compiled into a binary and in turn, the binary is run. Most codes often have bugs (mistakes in the code). These bugs can be used to have the binary hack the code.

Binary exploitation manipulates software flaws to control execution by hijacking programs, bypassing security for code execution, revealing critical vulnerabilitie, etc.

At its core, it involves analyzing the low-level execution of a program, i.e, how it uses memory, handles data, and controls its flow. The ultimate goal often being to achieve arbitrary code execution, allowing an attacker to run their own instructions on a target system.

Binary exploitation begins with ****Reverse Engineering****.


# REVERSE ENGINEERING
****Reverse engineering**** is the process of figuring out how a program's logic works and finding the weakness in it such as buffer overflows.

Buffer overflow occurs when input overruns a memory buffer, corrupting adjacent data critical target being the instruction pointer (a CPU register that dictates the next command to execute) By crafting input, an attacker can overwrite this pointer, seizing control of the program's execution flow. The exploit then redirects this flow to a payload of malicious machine code (shellcode) injected into memory or to existing beneficial program segments.

Modern systems deploy defenses like ****ASLR**** and ****DEP****, making exploitation more complex and requiring advanced techniques.

Ultimately, this field is crucial for cybersecurity, as understanding these offensive techniques is fundamental to building effective defenses and patching critical software vulnerabilities besides, most of the time you are just handed a binary and you have to figure out how it works, so you can attack it.
