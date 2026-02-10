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
