# Cisco Packet Tracer – Basic Switch Configuration and VLAN Setup

Introduction

Networking professionals and students often use Cisco Packet Tracer to simulate and test network configurations in a controlled environment. This project aims to guide users through the installation and setup of Packet Tracer, basic switch configuration, and VLAN assignments. By following these steps, users will gain hands-on experience in configuring a simple network with VLANs, which is a critical skill in enterprise networking.

This project will cover:

Installing and setting up Cisco Packet Tracer
Creating a simple network topology
Configuring basic switch settings
Assigning VLANs and verifying connectivity

![1 Cisco Packet Tracer Set Up](https://github.com/user-attachments/assets/c272807f-a532-4bfe-871d-ce5ffa8c2641)

Sections 

1.  Building a Simple Network Topology
-  Add a Cisco 2960 switch to the workspace
-  Add three end devices (PCs) and connect them to the switch using Ethernet cables
-  Assign static IP addresses to the PCs for network testing

The network will intially be set up with two PCs and a switch, connected by a straight-through cable as shown in the image below. Satic addresses will be assigned to the PCs.

![2](https://github.com/user-attachments/assets/27f08231-32de-4346-98d3-1fac6abfc19d)

Configuring the static IP address:

![3](https://github.com/user-attachments/assets/79a15faa-50ae-4d6c-b716-a96dca6ce153)

Current network configuration:

![4](https://github.com/user-attachments/assets/79a78d50-fcc6-41ef-b8a5-3041ccb29ee4)

We test the connection by pinging PC1 from PCO which is successful. 

![5](https://github.com/user-attachments/assets/68998ad5-0ea9-4c95-a820-9648a0963ded)

2. Creating and Assigning VLANs - Configuring the Switch
-  Create VLAN 2 (User VLAN) and VLAN 3 (Finance Dept. VLAN)
-  Assign the correct VLANs to the respective ports
-  Set access ports to restrict communication between VLANs

3. Verifying Connectivity and VLAN Segmentation
-  Use the ping command to test connectivity between PCs
-  Verify VLAN configurations using show VLAN command
-  Ensure VLAN separation and functionality
