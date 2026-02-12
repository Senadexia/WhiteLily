# WhiteLily

A Small and Lightweight Type-1 Research Hypervisor for Intel VT-x, built on UEFI.

## Overview
WhiteLily is a standalone, bare-metal hypervisor designed for hardware-assisted virtualization research and malware analysis. It operates at **Ring -1**, providing complete control over the guest operating system with minimal performance overhead.

## Current State (Alpha)
- [x] UEFI Bootloader integration (EDK II)
- [x] VMX Initialization & Successfull VM-Entry
- [x] Basic VMCS configuration (Optimized for Haswell and newer)
- [x] Research-ready logging system

## Architecture
WhiteLily is built from scratch as a solo project to explore the depths of x86-64 virtualization. It leverages Intel VT-x technology and runs as a UEFI Runtime Service to ensure early boot persistence.

## Roadmap
- [ ] EPT (Extended Page Tables) Implementation
- [ ] MMIO Interception (specifically for TPM 2.0 research)
- [ ] Stealth features (CPUID/MSR virtualization)

## Author
Developed by **Senadexia**. 
*This project is a result of independent research into low-level system security.*
<img width="1024" height="576" alt="image" src="https://github.com/user-attachments/assets/67a54615-7ab0-4069-ac95-d53b44119a8c" />

(sorry that hyper-v interface on russian it says that VM is work and loaded on 4%)
<img width="1118" height="551" alt="image" src="https://github.com/user-attachments/assets/6749dedb-7262-403f-9e23-1ea314f38f3f" />
