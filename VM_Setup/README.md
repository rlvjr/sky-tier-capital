<div align="center">

# Virtual Machine Setup

## Sky Tier Capital Server Deployment

</div>

---

## Purpose

This document covers the creation and initial configuration of the virtual machine used for the Sky Tier Capital infrastructure environment.

The virtual machine serves as the foundation for deploying Windows Server 2022 and enterprise services in an isolated lab environment.

---

## Virtualization Environment

| Component | Configuration |
|:---:|:---:|
| Hypervisor | Oracle VirtualBox |
| Host Operating System | macOS |
| Guest Operating System | Windows Server 2022 |
| Environment Type | Enterprise Simulation Lab |

---

## Virtual Machine Configuration

| Component | Configuration |
|:---:|:---:|
| Virtual Machine Name | SkyTierCapital-DC01 |
| Operating System | Windows Server 2022 Standard Evaluation |
| Virtual Disk Format | VirtualBox Disk Image (.vdi) |
| Network Adapter | VirtualBox Virtual Network Adapter |

---

## Deployment Process

The virtual machine was deployed using Oracle VirtualBox.

Configuration steps included:

1. Creating a new virtual machine
2. Allocating available system resources
3. Attaching the Windows Server 2022 installation media
4. Installing the operating system
5. Completing initial server configuration
6. Preparing the system for enterprise role deployment

---

## Initial Configuration

After installation, the following tasks were completed:

- Verified successful Windows Server installation
- Configured administrator access
- Confirmed system functionality
- Prepared networking configuration
- Installed required server roles

---

## Challenges Encountered

During deployment, troubleshooting was required for:

### System Resource Limitations

Virtual machine performance was optimized based on available host hardware resources.

### Storage Constraints

Disk space was managed to allow continued development of the infrastructure environment.

### Virtualization Configuration

Virtual machine settings were adjusted to resolve deployment and performance issues.

---

## Current Status

Completed:

- Virtual machine deployment
- Windows Server 2022 installation
- Initial server preparation
- Infrastructure role installation

Next Steps:

- Active Directory configuration
- DNS configuration
- Group Policy implementation
- User and access management

---

## Screenshots

Future documentation will include:

- Virtual machine settings
- Windows Server installation
- Server configuration
- Infrastructure services
