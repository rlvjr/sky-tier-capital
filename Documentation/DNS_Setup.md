<div align="center">

# DNS Setup

## Sky Tier Capital Domain Name Services

</div>

---

## Overview

DNS (Domain Name System) was implemented as a core infrastructure service within the Sky Tier Capital environment.

In an Active Directory environment, DNS provides the name resolution services required for domain communication, authentication, and locating network resources.

---

## DNS Configuration

| Component | Configuration |
|:---:|:---:|
| DNS Server | SkyTierCapital-DC01 |
| Domain | SkyTierCapital.local |
| Operating System | Windows Server 2022 |
| Service | Windows DNS Server |
| Environment | Active Directory Domain |

---

## Purpose of DNS

The DNS service provides:

- Internal hostname resolution
- Domain controller discovery
- Active Directory service communication
- Network resource identification

Active Directory relies heavily on DNS to locate domain services and allow computers and users to communicate within the domain environment.

---

## Implementation Completed

The following DNS-related tasks were completed:

- Installed DNS Server role on Windows Server 2022
- Configured DNS as part of the Active Directory deployment
- Verified DNS integration with the SkyTierCapital.local domain
- Prepared the environment for future client systems

---

## DNS Components

### Forward Lookup Zone

The forward lookup zone allows systems to resolve hostnames into IP addresses.

Example:

