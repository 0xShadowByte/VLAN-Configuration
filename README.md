# Basic Data and Voice VLAN Setup

### Objective
  
To set up an office network with four VLANs: one for regular office staff, one for HR, one for IT and one for VoIP (Voice over IP) devices like IP phones. A core switch will connect two access switches, and you will test connectivity between them.

### Skills Learned

- Networking Fundamentals: VLANs, core vs. access switches, trunk and access ports.
- Configuration & Management: VLAN setup, static IP assignment, trunk port setup.
- Hands-On Skills: Using Cisco Packet Tracer, connecting devices, configuring IP phones.
- Troubleshooting & Testing: Verifying connectivity, debugging VLAN issues.
- Security & Design: Controlling VLAN access, planning for DHCP and switch security.

### Tools Used

- CISCO Packet Tracer

### Steps

*Ref 1: Adding devices to homelab 5 PCs, 5 IP Phones and 3 Switches*

![image](https://github.com/user-attachments/assets/0843ac9d-425a-4394-8bb6-390be0d361b7)

*Ref 2: Connecting all devices together with copper straight-though connections. While connecting the switch to IP Phone and IP Phone to PC, connection could not be completed because it needs to be physically or manually turned on on packet tracer*

![image](https://github.com/user-attachments/assets/8b871e9e-4f13-4c30-95d7-275b603835cf)

*Ref 3: Open up IP Phone 0 on packet tracer so you'll see the physical phone. Click and drag the IP_PHONE_POWER_ADAPTER onto the power adapter port so the IP Phone can be turned on*

![image](https://github.com/user-attachments/assets/2e045fc6-f575-4a20-be31-9ee54163d0e3)

*Ref 4: Do the same to IP Phone 1 and the rest of the other devices*

![image](https://github.com/user-attachments/assets/fedaa707-0522-41cb-bf30-30f140ceaaaf)

*Ref 5: Use the same copper straight-through cable, gigabite ethernet0/1 and 0/2, to connect both access switches to the core switch*

![image](https://github.com/user-attachments/assets/16347da6-df69-4e88-a194-ceadc791dc04)

