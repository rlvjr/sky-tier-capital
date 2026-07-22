<div align="center">

# Asset Inventory

## Sky Tier Capital Infrastructure Assets

</div>

---

## Overview

This document provides an inventory of hardware, virtual machines, operating systems, and infrastructure components used within the Sky Tier Capital enterprise simulation environment.

The purpose of maintaining an asset inventory is to support organized system administration, lifecycle tracking, troubleshooting, and infrastructure management.

---

## Asset Management Objectives

The asset inventory helps maintain visibility into:

- Available systems and resources
- Hardware and software configurations
- Infrastructure dependencies
- System ownership and purpose
- Future expansion planning

---

# Infrastructure Assets

| Asset Name | Asset Type | Configuration | Purpose | Status |
|:---:|:---:|:---:|:---:|:---:|
| SkyTierCapital-DC01 | Virtual Server | Windows Server 2022 | Domain Controller / Infrastructure Server | Active |
| SkyTierCapital.local | Domain Environment | Active Directory Domain | Identity and Access Management | Active |
| VirtualBox Host Environment | Virtualization Platform | Oracle VirtualBox | Hosts enterprise lab systems | Active |

---

# Server Inventory

## SkyTierCapital-DC01

| Category | Details |
|:---:|:---:|
| System Type | Virtual Machine |
| Operating System | Windows Server 2022 Standard Evaluation |
| Primary Role | Domain Controller |
| Directory Service | Active Directory Domain Services |
| DNS Service | Windows DNS Server |
| Policy Management | Group Policy Management |
| Environment | SkyTierCapital.local |

---

# Installed Services

| Service | Purpose | Status |
|:---:|:---:|:---:|
| Active Directory Domain Services | Centralized authentication and identity management | Active |
| DNS Server | Internal name resolution | Active |
| Group Policy Management | Centralized configuration management | Active |
| Remote Server Administration Tools | Administrative management tools | Active |

---

# Virtualization Environment

| Component | Details |
|:---:|:---:|
| Hypervisor | Oracle VirtualBox |
| Host Operating System | macOS |
| Guest Operating System | Windows Server 2022 |
| Lab Purpose | Enterprise infrastructure simulation |

---

# Network Assets

| Asset | Purpose | Status |
|:---:|:---:|:---:|
| SkyTierCapital.local Domain | Internal authentication environment | Active |
| Domain Controller | Authentication and directory services | Active |
| DNS Server | Internal hostname resolution | Active |

---

# Future Assets

Planned additions to the environment:

- Windows client workstations
- Additional user systems
- Department-based devices
- Security monitoring solutions
- Backup solutions
- Additional servers

---

# Asset Management Practices

Future inventory expansion will include:

- Asset identification
- System ownership
- Software tracking
- Configuration documentation
- Lifecycle management
- Security review history

---

## Skills Demonstrated

This inventory demonstrates experience with:

- IT asset management
- Infrastructure documentation
- System administration
- Configuration tracking
- Enterprise environment organization
