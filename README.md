<h1 align="center">
🛡️ Surviving a Major Ransomware Event
</h1>

<p align="center">
<span style="color:#f97316"><b>Incident Response</b></span> •
<span style="color:#22c55e"><b>Infrastructure Recovery</b></span> •
<span style="color:#f97316"><b>Endpoint Remediation</b></span>
</p>

---

## 🟠 Overview

In **December**, our environment experienced a ransomware event impacting **150+ endpoints and critical infrastructure systems**.

The recovery required:

- Full **endpoint rebuilds**
- **Domain controller reconstruction**
- **Server backup restoration**
- **Cloud data recovery**
- Migration to a modern **Hybrid Active Directory + Intune** environment

The response required **Christmas hours, weekend recovery work, and coordination with MSP partners and enterprise recovery vendors** to restore operations quickly and securely.

---

## 🟢 Incident Timeline

### Initial Compromise
- Suspicious activity detected across endpoints
- Multiple workstations showing ransomware indicators
- Systems isolated to prevent further lateral movement

### Containment
- Compromised endpoints removed from network
- Server and domain services assessed for integrity
- Recovery plan coordinated with internal IT and vendor partners

---

## 🟠 Recovery Operations

### Endpoint Recovery
- Reimaged **150+ compromised endpoints**
- Rejoined devices to Active Directory
- Restored user profiles and configurations
- Validated systems before returning to production

### Data Recovery
- Restored user data from **OneDrive**
- Recovered server data from **verified backups**
- Validated file integrity and restored services

---

## 🟢 Infrastructure Rebuild

### Domain Services
- Rebuilt **Domain Controllers**
- Restored **Active Directory services**
- Reconfigured DNS and authentication systems

### Server Restoration
- Restored critical application servers
- Verified production services across the environment

---

## 🟠 Endpoint Protection Migration

The organization previously used **Comodo Endpoint Security**.

During recovery the environment transitioned to:

🛡 **CrowdStrike Falcon**

### Security Changes

- Removed legacy **Comodo security agents**
- Installed **CrowdStrike Falcon across all endpoints**
- Standardized enterprise endpoint protection

### Removal Challenges

Some endpoints required use of the **Comodo AV Agent Removal Tool** when administrative passwords failed to uninstall the agent.

During forced removal:

- **3 endpoints became unbootable**
- Required recovery or full system reimage
- Highlighted risks of legacy security tooling during incident response

---

## 🟢 Security Improvements

Following the recovery effort, several improvements were implemented.

### Device Management Modernization

- Implemented **Microsoft Intune**
- Established **Hybrid Active Directory**
- Centralized device compliance and management

### Endpoint Security Hardening

- Standardized endpoint protection with **CrowdStrike**
- Updated endpoint security policies
- Improved monitoring and remediation workflows

---

## 🟠 Technologies & Infrastructure Involved

### Identity & Directory Services

- Active Directory (AD DS)
- Domain Controller rebuild
- Hybrid Active Directory
- Azure AD / Microsoft Entra ID
- Group Policy Objects (GPO)

### Endpoint Management

- Microsoft Intune
- Hybrid Azure AD Join
- Device compliance policies
- Endpoint provisioning and lifecycle management

### Security Stack

- CrowdStrike Falcon (EDR)
- Comodo Endpoint Security (legacy AV)
- Malware remediation
- Endpoint security hardening

### Infrastructure

- Windows Server
- DNS & DHCP
- Enterprise endpoint environment
- Warehouse production IT infrastructure

---

## 🟢 Technical Skills Demonstrated

- Incident response & containment
- Enterprise endpoint recovery
- Active Directory infrastructure rebuild
- Server backup restoration
- Cloud data recovery (OneDrive)
- Antivirus migration & endpoint protection deployment
- Hybrid identity implementation
- Enterprise device management with Intune

---

## 🟠 Lessons Learned

This event reinforced several operational and security principles:

- Importance of **tested backups**
- Risks associated with **legacy security agents**
- Value of **centralized endpoint management**
- Need for **rapid containment procedures**

The organization returned to full operations with a **stronger, more resilient infrastructure**.

---

## 🟢 Wav Tech

**Infrastructure • Security • Incident Response**

Documenting real-world infrastructure challenges, recovery operations, and enterprise security improvements.
