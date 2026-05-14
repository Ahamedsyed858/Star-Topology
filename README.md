<img width="404" height="348" alt="image" src="https://github.com/user-attachments/assets/e0bdf24c-e31b-4b16-a766-2752a3ac7628" />Star Topology with 10 End Devices
Network Topology Report
1. Introduction
A Star Topology is a network configuration in which all devices are connected to a central device such as a switch or hub. All communication passes through this central device, making it the core of the network.
Star topology is widely used in modern networking because of its easy management, scalability, and high reliability. It is commonly used in LANs (Local Area Networks), offices, schools, and enterprise environments.

2. Concept of Star Topology
In a star topology:
Each node (PC) connects directly to a central switch 
Data flows from the source device → central switch → destination device 
The central switch controls and manages all communication 
Variants include:
Star (Single Switch) – One central switch (used in this experiment) 
Extended Star – Multiple switches connected hierarchically 
Wireless Star – Devices connect via an access point 
In this report, we use a Single Star Topology with 10 end devices in Cisco Packet Tracer.

3. Network Design for 10 End Devices
Structure Used: Star Topology
10 end devices (PC0–PC9) 
1 central switch (Switch0) 
Each PC is directly connected to the switch 
Communication tested using ICMP (Ping) 



4. Diagram Representation 
<img width="404" height="348" alt="image" src="https://github.com/user-attachments/assets/b5548e08-13a4-42e7-bc03-24b632d7774f" />
       

5. Cisco Packet Tracer Simulation
Simulation Screenshot 1 – Packet Initiated (PC1 → PC7)
- ICMP packet is sent from PC1
- Simulation starts at t = 0.000s
- Packet reaches the central switch first 

<img width="740" height="314" alt="image" src="https://github.com/user-attachments/assets/9f00da43-b8ab-4a73-a395-c36335b07668" />


Simulation Screenshot 2 – Packet at Switch (t ≈ 0.001s)
- Packet arrives at Switch0 
- Switch checks destination IP/MAC 
- Forwards packet to correct port 

<img width="693" height="294" alt="image" src="https://github.com/user-attachments/assets/4606a1ad-2549-4d8a-876e-9773b6be0f48" />


Simulation Screenshot 3 – Packet Forwarded to Destination (t ≈ 0.002s)
- Packet is forwarded from switch to PC7 
- Direct communication via central device 

<img width="691" height="356" alt="image" src="https://github.com/user-attachments/assets/55332891-3b17-4b1f-9cfb-1270cef7ecb6" />


Simulation Screenshot 4 – Packet Successfully Delivered
- Status: Successful 
- Packet Loss: 0% 
- Communication verified 

<img width="472" height="472" alt="image" src="https://github.com/user-attachments/assets/753d22f2-a5f7-432e-8a36-089481dbcc92" />

6. Components Required
Component	Quantity	Purpose
End Devices (PCs)	10	Source/Destination nodes
Switch (2950-24)	1	Central connecting device
Ethernet Cables	10+	Connect PCs to switch
IP Addresses	10	Unique addressing

7. Working Principle
1.Each PC is connected directly to Switch0 
2.When a device sends data: 
oIt first goes to the switch 
oSwitch reads destination address 
3.The switch forwards the packet only to the destination PC
Time taken: ~0.002 seconds 
Result: Successful, 0% packet loss 
8. Real-Time Scenario
Office Network Example
Star topology is commonly used in offices:
Employees’ computers connected to a central switch 
Printer, server, and internet also connected to same switch 
Advantages in real life:
Easy troubleshooting 
Fast communication 
Independent devices 
9. Advantages
Easy to install and manage 
Failure of one device does not affect others 
High performance due to dedicated links 
Easy to expand network 
Fault detection is simple 
10. Disadvantages
Central switch failure affects entire network 
More cabling required 
Higher cost compared to bus topology 
11. Applications
Office LAN networks 
School/college labs 
Banking systems 
Home networks 
Data centers 
12. Comparison with Other Topologies
Feature	Star Topology	Bus Topology	Ring Topology
Reliability	High	Low	Medium
Cost	Medium	Low	Medium
Scalability	High	Low	Low
Complexity	Low	Low	Medium
Collision	None	Possible	None
Fault Tolerance	High	Low	Medium

PART A – Match the Following
Column A	Column B
1. Switch	a. Ping protocol
2. ICMP	b. Central device
3. PC2	c. Source device
4. Ethernet Cable	d. Physical connection
5. IP Address	e. Unique identification
Answer Key:
1–b, 2–a, 3–c, 4–d, 5–e
PART B – True or False
1.Star topology uses a central device. (True) 
2.All devices are directly connected to each other. (False) 
3.Failure of one device affects the entire network. (False) 
4.Switch is used as a central device in star topology. (True) 
5.ICMP is used for testing connectivity. (True) 
6.Star topology requires less cabling than bus topology. (False) 
7.Each device has a dedicated link to the switch. (True) 
8.Data flows directly between devices without a switch. (False) 
9.Star topology is easy to troubleshoot. (True) 
10.Packet loss in a successful ping test is 0%. (True) 
PART C – Multiple Choice Questions (MCQs)
1.In star topology, devices are connected to:
a) Each other
b) A central device
c) A ring
d) A bus
Answer: b 
2. Which device is commonly used as the central node?
     a) Router
    b) Switch
     c) Hub
    d) Modem
    Answer: b 
3. Which protocol is used for connectivity testing?
a) HTTP
b) FTP
c) ICMP
d) SMTP
Answer: c 
4.What happens if the central switch fails?
a) Only one device fails
b) Entire network fails
c) No effect
d) Partial failure
Answer: b 
5.How many devices are used in this experiment?
a) 5
b) 8
c) 10
d) 12
Answer: c 
6.What is the result of a successful ping?
a) 100% loss
b) 50% loss
c) 0% packet loss
d) Timeout
Answer: c 
7.Star topology is mainly used in:
a) WAN
b) LAN
c) MAN
d) PAN
Answer: b




13.Conclusion
The Star Topology with 10 devices was successfully implemented in Cisco Packet Tracer using one central switch. All PCs were assigned unique IP addresses and tested using ICMP ping.
The communication between devices (e.g., PC1 to PC7) showed:
0% packet loss 
Successful transmission 
This proves that star topology provides efficient, reliable, and easy-to-manage communication, making it ideal for modern networking environments.
