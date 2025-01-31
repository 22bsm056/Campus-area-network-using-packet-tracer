Campus Network Design Using Cisco Packet Tracer and Network Attacks

📌 Project Overview

This project aims to design and simulate a secure and efficient campus network using Cisco Packet Tracer. It also includes a security analysis component where network attacks like brute force attacks on network services (FTP, Telnet) are demonstrated using Kali Linux tools like Hydra and Medusa.

🔥 Key Features

Campus Network Simulation using Cisco Packet Tracer.

IP Address Configuration for routers, switches, and end devices.

Wireless Network Setup with security implementation.

DNS, Email, and Web Server Configuration.

Network Security Measures including SSH encryption and password protection.

Brute Force Attack Simulation to analyze network vulnerabilities.

🎯 Objectives

Design a scalable and secure campus network using different networking devices.

Implement wireless networking to ensure mobility within the university.

Test network security by simulating brute force attacks.

Analyze vulnerabilities and propose mitigation strategies.

🖥️ Software & Hardware Requirements

✅ Software

Cisco Packet Tracer (for network simulation)

Kali Linux (for attack simulation)

VS Code or any text editor

Python (if scripting for automation is required)

✅ Hardware

Laptop with at least 8GB RAM

16GB of dedicated storage

Intel i5/AMD Ryzen 5 or better

📌 Network Architecture

🌐 Devices Used:

Device

Quantity

Router (1941)

4

Switches (2960-24TT, 3650)

52

Email Server

1

DNS Server

1

Web Server (HTTP)

1

PCs

16

Laptops

16

Printers

16

🏛️ Areas Covered

Hostel Blocks

Admin Blocks

Library

Academic Buildings

🔧 Configuration Summary

Main Router: Connects the entire network.

Subnetting: Different subnets for admin, hostel, and academic areas.

Servers: DNS, Email, Web (HTTP) servers configured.

Wireless Access Points: Secure Wi-Fi with SSID and password.

SSH Security: Secure remote access for network administrators.

🔄 Implementation Steps

🏗️ 1. Designing Network Topology

Placed routers, switches, and servers based on network requirements.

Connected subnets for different areas.

🛠️ 2. Configuring IP Addresses

Routers: Assigned static IPs to routers and servers.

Wireless Devices: Configured SSIDs and passwords.

🔐 3. Network Security

SSH enabled on routers for encrypted remote management.

Password protection for network access.

💥 4. Attack Simulation (Brute Force)

Tools Used: Hydra, Medusa (on Kali Linux)

Target Services: FTP, HTTP, SSH

Attack Method: Automated brute force login attempts.

Observation: Capturing failed/successful attempts using Packet Tracer.

🔬 Testing and Results

Network Configuration: Successfully established network connectivity.

Security Analysis: Demonstrated brute force vulnerability and importance of strong passwords.

Performance Evaluation: Analyzed packet flow and network traffic behavior.

📌 Future Work

Expand the attack simulations to include DDoS attacks.

Implement advanced firewalls for enhanced security.

Use AI-based anomaly detection for real-time threat analysis.

🤝 Team Members

Shubham Kumar (22bsm056)

Ankit Gopi (22bsm019)

Aryan (22bsm010)

Ayush Anand (22bsm011)

Dristi Kushwaha (22bsm018)

📌 Supervised By

Dr. Sachin Kumar Saxena (Department of Mechanical Engineering, IIITDM Jabalpur)

📜 References

Cisco Packet Tracer Documentation

Networking Fundamentals (Cisco Academy)

Kali Linux Documentation

Hydra, Medusa Official Docs

📂 Repository Structure

📦 Campus-Network-Simulation
├── 📁 Configurations
│   ├── router_config.txt
│   ├── switch_config.txt
│   ├── server_config.txt
├── 📁 Simulations
│   ├── network_topology.pkt
│   ├── attack_simulation.pkt
├── 📁 Reports
│   ├── Mid-Term Report.pdf
│   ├── Final Report.pdf
├── README.md

🚀 How to Run the Project

1️⃣ Set Up Cisco Packet Tracer

Download and install Cisco Packet Tracer.

Open network_topology.pkt to view the simulation.

2️⃣ Run Security Testing

Install Kali Linux.

Run Hydra/Medusa to test brute force attacks:

hydra -l admin -P passwords.txt ftp://192.168.1.1

3️⃣ Monitor Traffic in Packet Tracer

Use Simulation Mode to track packets and security events.

🏆 Conclusion

This project successfully simulates a campus-wide network while also analyzing network security threats. Through the use of Packet Tracer and Kali Linux, it highlights the importance of proper network design and security measures in a university setup.

"A secure network is a functional network." 🔒🚀

📧 Contact

For queries, feel free to reach out:

📧 Email: 22bsm056@iiitdmj.ac.in
