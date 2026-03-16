# Surviving a Major Ransomware Event

## Overview
In December, our environment experienced a ransomware event that impacted over **150 endpoints and critical infrastructure systems**. Immediate containment, system recovery, and infrastructure rebuilding were required to restore business operations.

The recovery process involved rebuilding domain infrastructure, restoring server backups and cloud data, reimaging compromised endpoints, and strengthening the security posture of the environment moving forward.

---

## Incident Timeline

### Initial Compromise
- Suspicious system behavior and widespread endpoint impact identified
- Multiple systems displaying ransomware indicators
- Workstations and servers taken offline to prevent further spread

### Containment
- Isolated compromised endpoints from the network
- Assessed affected infrastructure including servers and domain services
- Identified scope of impact across the environment

---

## Recovery Operations

### Endpoint Recovery
- Reimaged **150+ compromised endpoints**
- Rejoined devices to the domain
- Restored user profiles and workstation configurations
- Verified systems before returning them to production

### Data Recovery
- Restored user files from **OneDrive**
- Recovered critical server data from verified backups
- Validated integrity of restored files and services

---

## Infrastructure Rebuild

### Domain Services
- Rebuilt **Domain Controllers**
- Restored **Active Directory services**
- Reconfigured DNS and authentication services

### Server Restoration
- Restored application servers from backup
- Verified service functionality across the environment

---

## Endpoint Protection Migration

The environment previously used **Comodo Endpoint Security**. During recovery, the organization migrated to **CrowdStrike Falcon** for improved endpoint protection and threat detection.

### Security Changes
- Removed legacy **Comodo security agents**
- Installed **CrowdStrike Falcon** across all endpoints
- Standardized endpoint protection platform

### Agent Removal Challenges
Some endpoints required use of the **Comodo AV Agent Removal Tool** due to administrative password restrictions preventing normal removal.

During forced removal:

- 3 endpoints became unbootable
- Systems required recovery or full reimage
- Highlighted risks associated with legacy security agents during incident response

---

## Security Improvements

Following recovery, several improvements were implemented to strengthen the environment.

### Device Management Modernization
- Implemented **Microsoft Intune**
- Established **Hybrid Active Directory environment**
- Enabled centralized device compliance and management

### Endpoint Security Hardening
- Standardized endpoint protection using CrowdStrike
- Updated security policies
- Improved monitoring and remediation procedures

---

## Technologies & Infrastructure Involved

### Identity & Directory Services
- Active Directory (AD DS)
- Domain Controller rebuild & promotion
- Hybrid Active Directory
- Azure AD / Microsoft Entra ID
- Group Policy Objects (GPO)

### Endpoint Management
- Microsoft Intune
- Hybrid Azure AD Join
- Device enrollment and compliance policies
- Endpoint provisioning and lifecycle management

### Security Stack
- CrowdStrike Falcon (Endpoint Detection & Response)
- Comodo Endpoint Security (legacy AV)
- Malware remediation and endpoint hardening

### Infrastructure
- Windows Server
- DNS & DHCP
- Enterprise endpoint environment
- Production warehouse IT infrastructure

---

## Technical Skills Demonstrated

- Incident response and containment
- Endpoint recovery and OS deployment
- Active Directory infrastructure rebuild
- Server backup restoration
- Cloud data recovery (OneDrive)
- Endpoint protection migration
- Enterprise endpoint management
- Hybrid identity implementation

---

## Lessons Learned

This incident reinforced several key operational and security principles:

- Importance of reliable and tested backups
- Risks associated with legacy security tools
- Value of centralized device management
- Importance of rapid containment and recovery procedures

The environment was successfully restored and strengthened with improved endpoint management and security controls.

---

## Wav Tech

**Infrastructure | Security | Incident Response**

Documenting real-world infrastructure challenges and recovery operations.
