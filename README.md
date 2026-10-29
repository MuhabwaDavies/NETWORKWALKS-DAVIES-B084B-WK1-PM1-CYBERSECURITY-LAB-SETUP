# **Cybersecurity Lab Environment Setup**
## **Project overview**
In this project i built a virtual cybersecurity lab using VirtualBox and Kali Linux. The main goal is to create a safe environment where I can practice cybersecurity skills, explore different security tools, scan networks, gather information, and identify potential vulnerabilities.

The lab runs on a private virtual network, allowing me to add more virtual machines in the future and use them for hands-on security testing. This setup provides a practical way to learn, experiment, and improve my penetration-testing skills without affecting real systems or networks.
## Project objectives
- Install and configure VirtualBox.
- Install/import Kali Linux as a virtual machine.
- Create a private NAT Network for the cybersecurity lab.
- Configure network connectivity for Kali Linux.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the complete setup process.
- Prepare the environment for future cybersecurity projects.
## Purpose of the Lab
This lab can be used for activities such as: Network reconnaissance, Port scanning, Vulnerability assessment, Packet analysis, Web security testing and so on.
## Lab Configuration
| Component          | Configuration        |
| ------------------ | -------------------- |
| Host OS        | Windows 11          |
| Host RAM        | 16 GB                 |
| Hypervisor      | VirtualBox 7.2       |
| Security OS     | Kali Linux 2026.21    |
| Kali RAM        | 2048 MB (2 GB)       |
| Virtual Network | NAT Network          |
| Network Address | `10.0.0.0/24`        |
| Kali IP Address | `10.0.0.2/24`        |
| Default Gateway | `10.0.0.1`           |
| DNS Server      | `8.8.8.8`            |
| Future VM Range | `10.0.0.3–10.0.0.99` |

## Lab Setup Procedure
# Step 1. Install VirtualBox
VirtualBox was installed as the hypervisor.
# Step 2. Create the NAT Network
A dedicated NAT Network was created in VirtualBox.

Configuration: Network Name is "NatNetwork" IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled
