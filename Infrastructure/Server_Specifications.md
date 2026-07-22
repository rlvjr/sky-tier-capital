<div align="center">

# Server Specifications

## Sky Tier Capital Infrastructure Server

</div>

---

## Overview

This document outlines the hardware and software specifications of the primary server used within the Sky Tier Capital enterprise simulation environment.

The server functions as the foundation of the infrastructure, providing core enterprise services including Active Directory, DNS, and Group Policy management.

---

## Server Identification

| Component | Details |
|:---:|:---:|
| Server Name | SkyTierCapital-DC01 |
| Server Role | Domain Controller |
| Environment | SkyTierCapital.local |
| System Type | Virtual Machine |
| Purpose | Enterprise Infrastructure Services |

---

## Operating System

| Component | Specification |
|:---:|:---:|
| Operating System | Windows Server 2022 Standard Evaluation |
| Installation Type | Virtual Machine Deployment |
| Server Role | Domain Controller |
| Authentication System | Active Directory Domain Services |

---

## Virtual Machine Specifications

| Component | Allocation |
|:---:|:---:|
| Virtualization Platform | Oracle VirtualBox |
| Virtual Disk | VirtualBox Disk Image (.vdi) |
| Network Mode | Virtual Network Adapter |
| Deployment Type | Enterprise Lab Simulation |

---

## Installed Server Roles

### Active Directory Domain Services (AD DS)

Purpose:

Provides centralized identity management and authentication services.

Capabilities:

- User account management
- Domain authentication
- Computer account management
- Security group administration

---

### DNS Server

Purpose:

Provides internal domain name resolution services.

Capabilities:

- Resolves internal hostnames
- Supports Active Directory communication
- Enables domain service discovery

---

### Group Policy Management

Purpose:

Provides centralized configuration and security management.

Capabilities:

- User configuration
- Computer configuration
- Security policy enforcement
- Administrative control

---

## Server Responsibilities

The primary responsibilities of SkyTierCapital-DC01 include:

- Managing domain authentication
- Maintaining directory services
- Providing DNS resolution
- Supporting administrative operations
- Hosting enterprise management services

---

## Security Considerations

Security practices implemented or planned:

- Domain-based authentication
- Controlled administrative access
- Centralized user management
- Security policy enforcement through Group Policy
- Documentation of configuration changes

---

## Future Expansion

Planned infrastructure improvements:

- Additional virtual servers
- Domain-connected client machines
- Dedicated file services
- Backup implementation
- Security monitoring tools
- Additional administrative roles

---

## Skills Demonstrated

This server deployment demonstrates experience with:

- Windows Server administration
- Virtual machine deployment
- Enterprise service configuration
- Infrastructure documentation
- Identity and access management
