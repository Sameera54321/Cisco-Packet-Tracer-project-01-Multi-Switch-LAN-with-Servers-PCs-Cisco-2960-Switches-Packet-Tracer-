# Multi-Switch-LAN-with-Servers-PCs-Cisco-2960-Switches-Packet-Tracer-
I’m happy to share a straightforward but essential networking project – a multi‑switch LAN built in Cisco Packet Tracer. The topology includes three Cisco 2960‑24TT switches, two servers (Server1, Server2), and six client PCs (PC0 – PC5).

![image alt](https://github.com/Sameera54321/Multi-Switch-LAN-with-Servers-PCs-Cisco-2960-Switches-Packet-Tracer-/blob/main/21.png?raw=true)

## 📌 Summary

Multi‑Switch LAN is a Cisco Packet Tracer simulation that models a small to medium‑sized switched network. The topology includes:

    3 switches – Cisco 2960‑24TT (Switch1, Switch2, Switch3)

    2 servers – Server1 and Server2 (can provide DHCP, DNS, HTTP, FTP)

    6 client PCs – PC0 through PC5

### Typical IP addressing (example):

| Device | IP Address | Subnet Mask | Default Gateway |
| :--- | :--- | :--- | :--- |
| Server1 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| Server2 | 192.168.1.20 | 255.255.255.0 | 192.168.1.1 |
| PC0 - PC5 | 192.168.1.100-105 | 255.255.255.0 | 192.168.1.1 |

### Key configurations:

    Switch basics – hostnames, passwords, management IP (optional)

    STP – enabled by default; observe root bridge election

    VLANs (optional) – create multiple VLANs and assign ports

    Server services – configure DHCP on Server1 to assign IPs to PCs

### Verification:
ping from any PC to any server should succeed if all are in the same subnet and switches are correctly connected.

## ✨ Features

    ✅ 3 Cisco 2960 switches – Layer 2 connectivity, STP, VLAN capable

    ✅ 2 servers – can run DHCP, DNS, HTTP, FTP

    ✅ 6 client PCs – test connectivity and server access

    ✅ Full Packet Tracer file (.pkt) – ready to open and experiment

    ✅ Documentation – IP plan, switch configs, server setup

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – switch and server configurations

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add a router to provide inter‑VLAN routing or internet access.

    Implement VLANs and trunking between switches.

    Configure STP enhancements (PortFast, BPDUguard).

    Add more PCs or servers.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
