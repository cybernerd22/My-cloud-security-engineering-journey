# Phase 1 — IT Fundamentals

**Duration:** Weeks 2–5

Objective

The goal is not to become a computer technician. The goal is to understand how computer systems operate so that I understand what I am securing as I progress toward Cloud Security Engineering.

I need operational understanding, not electrical-engineering depth.

1.1 Computer Architecture

Topics

* CPU
* RAM
* Storage
* Motherboard
* BIOS/UEFI
* Boot process
* Firmware
* Drivers
* Interrupts
* Processes

Expected capability

Explain how a computer starts, executes instructions, uses memory and storage, and communicates with hardware.

1.2 Operating Systems

Topics

* Kernel
* User space
* Processes
* Threads
* Memory
* Filesystems
* Drivers
* Services
* System calls

Operating system model

text
Application
    ↓
Libraries
    ↓
System calls
    ↓
Kernel
    ↓
Hardware
``

Expected capability

Explain the responsibilities of the operating system, distinguish user space from kernel space, and describe how applications request operating-system services.

1.3 Windows Administration

Topics

* Users
* Groups
* NTFS
* Permissions
* Services
* Processes
* Event Viewer
* Task Manager
* PowerShell basics
* Windows Firewall

### Practical labs

In a controlled environment:

* Stop a service and investigate its effects.
* Investigate disk usage and simulate a low-disk-space condition safely.
* Create a user.
* Change and verify permissions.
* Disable and re-enable a service.
* Generate and inspect login events.
* Troubleshoot problems and restore the original system state.

### Expected capability

Administer basic Windows resources, inspect relevant logs, understand access permissions, diagnose problems, and restore changes safely.

## 1.4 Virtualization

### Topics

* Hypervisor
* Virtual machine (VM)
* Virtual disk
* Virtual network interface (NIC)
* Snapshots
* NAT networking
* Bridged networking
* Host-only networking

Target lab architecture

text
Physical Host — Windows 11
          |
       VirtualBox
          |
     +----+----+
     |         |
 Windows VM  Ubuntu VM
``

The Windows VM will be used for controlled Windows administration exercises if the host's available resources permit. The existing Ubuntu Server VM will be used for Linux practice.

Expected capability

Explain how virtual machines use host resources, distinguish virtual networking modes, create and manage snapshots where supported, and restore a VM to a known-good state.

Learning Method

For each topic, follow this cycle:

Learn → Practice → Build → Break → Investigate → Fix → Verify → Explain → Document**

Each major lesson should include:

1. Concept and mental model.
2. Guided demonstration.
3. Hands-on practice.
4. Troubleshooting based on evidence.
5. Independent challenge.
6. Knowledge check and assessment.
7. Documentation of results.

Documentation Standard

For each practical lab, record:

* Objective
* Environment
* Steps performed
* Expected result
* Actual result
* Evidence and observations
* Problems encountered
* Root cause
* Fix and verification
* Security implications
* Lessons learned

Completion Criteria

Phase 1 is complete when I can:

* Explain the listed architecture and operating-system concepts in my own words.
* Demonstrate basic Windows administration tasks safely.
* Inspect relevant processes, services, permissions, and event logs.
* Explain the difference between a physical host and a virtual machine.
* Explain NAT, bridged, and host-only networking.
* Troubleshoot a controlled failure using evidence rather than guessing.
* Restore changes and document the result.
* Explain why these foundations matter for cybersecurity and cloud security.

Connection to Cloud Security Engineering

These foundations prepare me to understand operating systems running on cloud instances, identity and permissions, service exposure, network isolation, system logs, and security investigations. Later phases will build on these concepts rather than skip them.
