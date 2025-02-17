# Setup The Attacker Machine

## Table of Contents

- [Prerequisites](#prerequisites)
- [Network Topology](#network-topology)
- [Kali Linux Overview](#kali-linux-overview)
  - [What is Kali Linux?](#what-is-kali-linux)
  - [How is Kali Linux Used?](#how-is-kali-linux-used)
- [Security Implications](#security-implications)
- [Configure Kali Linux](#configure-kali-linux)
- [Optional](#optional)
  - [Disable Default Logoff](#disable-default-logoff)

## Prerequisites

1. **Virtual Box Installed.**
2. **Virtual Machine with Kali Linux ISO** has been configured and provisioned (the ISO should be attached to the new VM).

## Network Topology

*Content not provided.*

## Kali Linux Overview

### What is Kali Linux?

Kali Linux is a specialized Linux distribution tailored for cybersecurity professionals and ethical hackers. Developed by Offensive Security, it is a Debian-based operating system preloaded with tools designed for penetration testing, ethical hacking, and digital forensics. Kali Linux is widely used for assessing system vulnerabilities, testing network security, and investigating cyber incidents.

Kali comes with a suite of security tools to assist in the operations.

### How is Kali Linux Used?

Kali Linux serves multiple purposes in the cybersecurity field, including:

1. **Penetration Testing:**  
   Professionals use Kali Linux to simulate real-world cyberattacks and identify vulnerabilities in systems, networks, and applications. Tools like Metasploit and Burp Suite are often employed in these scenarios.

2. **Vulnerability Assessment:**  
   It provides tools to scan and identify weaknesses in infrastructure, ensuring they are addressed before exploitation.

3. **Cybersecurity Training:**  
   Kali Linux is widely used in cybersecurity training programs, competitions, and certifications.

## Security Implications

Leveraging an operating system like Kali Linux carries certain benefits and risks.

**Benefits:**

- Can be used by trained professionals to help understand their organizational security controls and identify vulnerabilities before actors can exploit them.
- Offers a platform to safely practice offense security techniques in controlled environments.
- Tools are aggregated in one centralized ecosystem.

**Risks:**

- This tool can also be used maliciously by attackers if accessed by unauthorized individuals.
- Kali Linux is not meant to be a production environment without isolation. Be careful.

## Configure Kali Linux

**Step 1:**

- Choose the default “Graphical install”.
- Choose Language → “Continue”.
- Choose the Country and Keyboard layout.
- Change the hostname from *Kali* to *attacker* → “Continue”.
- Leave the domain name empty → “Continue”.
- Add “attacker” as the new user and username.
- Enter “attacker” as the default password → “Continue”.  
  *Refer to the “Project Overview” guide for more information on default usernames and passwords.*
- Choose a time zone of your choice for the clock option → “Continue.”
- Select “Guided – use entire disk” → “Continue.” Keep all defaults selected.
- Change “Write the changes to disks?” to “Yes” → “Continue.”
- Keep defaults selected → “Continue”. Wait for the software to install.
- Install the GRUB Loader.
- Select “Continue” and allow the system to reboot.
- Login under the *attacker* account.
- **Success!**
- **Take Snapshot!**

## Optional

### Disable Default Logoff

- Go to the Menu Bar → “Power Manager”.
- Navigate to the “Display” tab → Drag Toggle to the left.
