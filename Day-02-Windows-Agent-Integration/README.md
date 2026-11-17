# Day 02 – Windows Agent Integration

## Overview

Day 2 of my 7-day hands-on project: **Building a Security Operations Center (SOC) Lab Using Wazuh**.

In this phase, I integrated a Windows 10 endpoint with the Wazuh server running on Ubuntu inside VMware.

## Objectives

- Configure VMware network connectivity.
- Install Wazuh Agent on Windows 10.
- Configure the agent to communicate with the Wazuh Manager.
- Register the Windows endpoint.
- Verify agent connectivity through the Wazuh Dashboard.

## Lab Environment

| Component | Configuration |
|---|---|
| Virtualization | VMware |
| Server OS | Ubuntu Linux |
| Endpoint OS | Windows 10 |
| Security Platform | Wazuh 4.14.9 |
| Agent Name | DAFYD-Windows |

## Implementation

### 1. Network Configuration
- Configured VMware networking for the Windows 10 virtual machine.
- Established network connectivity between the endpoint and server.
- Verified connectivity using network diagnostic commands.

### 2. Wazuh Agent Installation
- Downloaded the Wazuh Windows Agent.
- Configured the Wazuh Manager IP address.
- Set the agent name to DAFYD-Windows.
- Installed the Wazuh Agent.

### 3. Agent Integration
- Connected the Windows endpoint to the Wazuh Manager.
- Started the Wazuh Agent service.
- Verified agent registration and connectivity through the Wazuh Dashboard.

## Screenshots

Add your implementation screenshots below.

## Outcome

Successfully integrated a Windows 10 endpoint with the Ubuntu-based Wazuh server, establishing the foundation for centralized endpoint security monitoring.

## Key Learnings

- VMware virtual networking and connectivity.
- Wazuh Agent installation and configuration.
- Communication between Wazuh Agent and Manager.
- Endpoint registration and monitoring.

## Next Steps – Day 03

- Configure Sysmon on Windows.
- Collect detailed Windows system activity logs.
- Integrate Sysmon events with Wazuh.
- Explore endpoint security monitoring.

---

**Project:** Building a SOC Lab Using Wazuh

**Progress:** Day 2 / 7 – Completed