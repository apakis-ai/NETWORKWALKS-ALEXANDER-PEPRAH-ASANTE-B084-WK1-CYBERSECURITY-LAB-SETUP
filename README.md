# NETWORKWALKS-ALEXANDER-PEPRAH-ASANTE-B084-WK1-CYBERSECURITY-LAB-SETUP
This is my first Cybersecurity Lab setup


📌 Project Overview

Thw focus of this project is to setup a virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.

The main purpose of the lab is to create a controlled environment where cybersecurity tools, network scanning, reconnaissance, vulnerability assessment, and other security-testing activities can be done and undone in a safe environment.

This lab is configured on a private virtual network that allows additional machines can be added later and used as targets for authorized security testing.


🎯 Objectives

The main objectives of this project are to:

    Install and configure VirtualBox.
    Install/import Kali Linux as a virtual machine.
    Create a private NAT Network for the cybersecurity lab.
    Configure network connectivity for Kali Linux.
    Assign a consistent IP address to the Kali VM.
    Verify network connectivity and DNS resolution.
    Take a clean VM snapshot for recovery.
    Document the complete setup process.
    Prepare the environment for future cybersecurity projects.


🛡️ Purpose of the Lab

The lab gives an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

    Network reconnaissance
    Port scanning
    Vulnerability assessment
    Packet analysis
    Web security testing
    Exploitation practice
    Security-tool experimentation

> [⚠️ Important]: 
> This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.

🏗️ Lab Architecture

<img width="1346" height="616" alt="1-screenshot-title-image" src="https://github.com/user-attachments/assets/4f63ba8d-9758-47a4-854c-b5e699c262ab" />


Additional target machines can be added to the same virtual network in future projects.

⚙️ Lab Configuration
________________________________________
|🧩 Component     |	   ⚙️ Configuration|
________________________________________
|🖥️ Host OS       |        Windows 10  |
|_________________|___________________|___
|🧠 Host RAM 	    |      8 GB          |
⚡ Processor 	           Intel Core i7
🧰 Hypervisor 	         VirtualBox 7.2
🐉 Security OS 	         Kali Linux 2026.2
🧠 Kali RAM 	           2048 MB
🌐 Virtual Network       NAT Network
📡 Network Address    	 10.0.0.0/24
🐧 Kali IP Address 	     10.0.0.2/24
🚪 Default Gateway    	 10.0.0.1
🌍 DNS Server 	         8.8.8.8
🔮 Future VM Range    	 10.0.0.3–10.0.0.99


🪜 Lab Setup Procedure
Step 1. Install 7-Zip

7-Zip was installed to extract the Kali Linux virtual-machine package, which may be distributed as a .7z archive.

Tool: 7-Zip
Step 2. Install VirtualBox

VirtualBox was installed as the hypervisor.
Step 3. Create the NAT Network

A dedicated NAT Network was created in VirtualBox.

Configuration: Network Name: NatNetwork IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabled
