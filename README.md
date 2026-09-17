Kali Linux Network Setup Lab (Week 1)
📌 Project Overview
This project documents my Week 1 Kali Linux lab setup using Oracle VirtualBox.
The main objective was to configure the virtual machine network, assign an IPv4 address, configure DNS, and verify internet connectivity.

🛠️ Tools Used
Kali Linux
Oracle VirtualBox
NetworkManager (nmcli)
Linux networking commands
Google DNS (8.8.8.8)
⚙️ Network Configuration
Setting	Value
Virtualization Software	Oracle VirtualBox
Network Mode	NAT Network
NAT Network Name	NatNetwork
IPv4 Network	10.0.0.0/24
Kali Linux IP Address	10.0.0.2/24
Gateway	10.0.0.1
DNS Server	8.8.8.8
Network Interface	eth0
🧪 Tasks Completed
 Created and configured a NAT Network in VirtualBox
 Checked the network interface using ip addr
 Checked device status using nmcli device status
 Viewed the available network connection
 Configured a manual IPv4 address
 Configured the gateway and DNS server
 Activated the wired connection
 Verified internet connectivity using ping google.com
 Created a VirtualBox snapshot named week1-Setup-Complete
📸 Screenshots
1. Checking Network Interfaces
Checking network interfaces

2. Checking NetworkManager Device Status
NetworkManager device status

3. Configuring the Wired Connection
Wired connection configuration

4. VirtualBox NAT Network Configuration
VirtualBox NAT Network

5. Successful Internet Connectivity Test
Successful ping test

✅ Result
The Kali Linux virtual machine was successfully configured with a NAT Network and a manual IPv4 configuration. Internet connectivity was verified using the ping command.

🎯 Learning Outcomes
Through this lab, I learned:

Basic Linux network troubleshooting
How to configure network connections using nmcli
IPv4 addressing and gateway configuration
DNS configuration
Network verification using ping
Managing snapshots in Oracle VirtualBox
Author: Gokul R
Field: B.Sc. Computer Science with Cyber Security
