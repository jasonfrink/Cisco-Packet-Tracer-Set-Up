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

We test the connection by pinging PC1 from PC0 which is successful. 

![5](https://github.com/user-attachments/assets/68998ad5-0ea9-4c95-a820-9648a0963ded)

2. Creating and Assigning VLANs - Configuring the Switch
-  Create VLAN 2 (User VLAN) and VLAN 3 (Finance Dept. VLAN)
-  Assign the correct VLANs to the respective ports
-  Set access ports to restrict communication between VLANs
-  Verify VLAN configurations using show VLAN command
-  Test connectivity with Ping command

![6](https://github.com/user-attachments/assets/ac685170-bda3-4799-b2f8-23f3954b5a76)

Use the switch CLI to set up the VLANs:

![6](https://github.com/user-attachments/assets/79580b81-7d4d-4b31-ab33-c1044836073c)

Use the Switch CLI to set up access port and assign respective VLAN:

![8](https://github.com/user-attachments/assets/8809e028-7594-4229-83ae-b77450fd0343)

Check to see if the access ports have been assigned correctly:

![9](https://github.com/user-attachments/assets/e6b0a48a-ebe8-4315-8cd2-c9eab710a8d1)

Ping request from PC0 to PC1 should fail if access ports configured properly:

![10](https://github.com/user-attachments/assets/e567f086-eec4-46b0-83e4-cdec6a5f3b22)

3. Add PC02 to network
-  Configure PC02 with static IP
-  Assign PC03 to to VLAN3
-  Ensure VLAN separation and functionality
-  Use the ping command to test connectivity between PCs


