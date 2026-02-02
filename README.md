# Projects

# Port Security Lab

## Objective

The Port Security Lab aimed to configure port security on a Cisco switch using Cisco Packet Tracer. The objective is to populate the MAC address table, apply port security polices, and test the system for violations to ensure secure network functionality.

### Skills learned 

 - Skill in configuring network devices
 - Troubleshoot hardware/software interface and interoperability problems
 - Skill in configuring software-based computer protection tools

### Tools Used

- Cisco Packet Tracer for a virtualized environment where we could configure different devices such as computers and swicthes for this lab.

## Steps

1st - Populate the MAC address table of the switch by using the ping command from Mike's PC to every other other computer
<img width="1213" height="688" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/70bd44e0-84c6-49f5-b849-811bb2a5f94c" />

2nd - Display the MAC address table from the CLI interface in the switch
<img width="3840" height="1276" alt="Screenshot (17)" src="https://github.com/user-attachments/assets/5f1e4616-c5e5-4b07-817d-3181a07b5157" />

3rd - Access the switchs configure mode and dnable port security on the following interfaces: fastethernet 0/1, fastethernet 0/2, and fastethernet 0/3
<img width="1113" height="605" alt="Screenshot (16)" src="https://github.com/user-attachments/assets/e47902b8-0f4e-421a-8ba1-269d3c606dd1" />

4th - Set the authorized MAC addresses for fastethernet 0/1 and fastethernet 0/2 to be fixed to the currently assigned MAC address according to the MAC address table
