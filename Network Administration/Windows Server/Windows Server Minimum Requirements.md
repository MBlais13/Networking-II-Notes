#NetAdmin #WindowsServer 

| Table 1-2: Minimum hardware requirements for Windows Server 2019 |                                                                                                                                |                                                                                                                                                                                                                        |
| ---------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Hardware                                                         | Minimum requirements                                                                                                           | Additional considerations                                                                                                                                                                                              |
| Basic Input/Output System (BIOS)                                 | Unified Extensible Firmware Interface (UEFI) 2.3.1c BIOS or higher for physical server installation                            | Trusted Platform Module (TPM) is also required for secure boot and encryption features.                                                                                                                                |
| Processor                                                        | 1.4 GHz 64-bit processor (includes support for NX, DEP, CMPXCHG16b, LAHF/SAHF, PrefetchW, EPT, or NPT)                         | Processor clock speed, amount of processor cache, and number of processor cores should be considered based on planned usage. Hyper-V also requires processor virtualization extensions (Intel VT or AMD-V, with SLAT). |
| Memory                                                           | 512 MB (2 GB for a server with the GUI desktop)                                                                                | Each virtual machine requires 800 MB for setup (although this can be scaled back after setup is complete). ECC memory is recommended for physical (non-virtualized) server installations.                              |
| Storage                                                          | 32 GB                                                                                                                          | 32 GB is the minimum for Server Core, while 36 GB is the minimum for installing a full Windows Server.                                                                                                                 |
| Network interface                                                | 1 gigabit or faster Ethernet adapter that is compatible with PCI Express architecture and Pre-boot Execution Environment (PXE) | Additional adapters are recommended if you support  <br>multiple virtual machines.                                                                                                                                     |
| Optical drive                                                    | DVD drive (optional)                                                                                                           | While a DVD drive is needed for installations from DVD media, many administrators install from a USB  <br>drive today.                                                                                                 |
| Display                                                          | Super VGA at 1024 3 768 or higher resolution                                                                                   | Multiple servers can share one display via the use of a keyboard video-mouse (KVM) switch.                                                                                                                             |
| Interactive devices                                              | Keyboard and pointing device                                                                                                   | Multiple servers can share a keyboard and pointing device via the use of a KVM switch box.                                                                                                                             |