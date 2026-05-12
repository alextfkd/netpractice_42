*This project has been created as part of the 42 curriculum by tkatsuma.*

# NetPractice (version 6.0)

## Description

This project is a tool to help me practice the network concepts and skills. This project utilizes the NetPractice exercise (version 6.0) from 42. This project is a web application that allows me to practice the network concepts and skills by solving the exercises.

### Submission details

This repository contains json configuration file from the 10 execerises. Each json file contains the configuration of the network topology and the routes.

```
.
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
├── level10.json
└── README.md
```

## Instructions

1. First, download the file attached to the project’s page.
2. Then, extract the files in whatever folder you want.
3. In this folder, run the index.html file.
4. The evaluation / training interface should open in your web browser.

## Resources

### The networking concepts studied

- TCP/IP addressing: This is a way of giving every device on a network its own unique number (IP address) so they can talk to each other. TCP/IP is a protocol that is used to send and receive data over a network. It is a set of rules that governs how data is sent and received over a network. It is a layer 3 protocol that is used to send and receive data over a network.

- Subnet mask: This helps divide a big network into smaller parts, making it easier to manage and more secure. The subnet mask is a 32-bit number that is used to identify the network part and the host part of an IP address. It could be represented as a decimal number or a bitmask. (e.g. 255.255.255.0 or /24). The subnet mask devides the IP address into network part and host part. The network part is the part that is used to identify the network, and the host part is the part that is used to identify the host.

- Default gateway: This is the device (usually a router) that connects your local network to other networks, like the internet. It is the IP address of the router that is used to send and receive data to other networks. 

- Switches: Devices that connect multiple computers within the same local network and help them communicate efficiently. The network part of the IP address is the same for all devices connected to the switch.

- Routers: Devices that forward data between different networks, helping your information get to where it needs to go. The network part of the IP address is different for each network connected to the router.

- Routing table: A table that contains the routes to other networks. It is used to forward data to the correct network. Each host and router has its own routing table. By default, the routing table contains the routes to the local network and the default gateway.

- OSI layers: A model with 7 stacked layers that explain how data travels from one computer to another over a network, step by step. 

    - Layer 1: Physical layer. This is the physical layer of the OSI model. It is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 2: Data link layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 3: Network layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 4: Transport layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 5: Session layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 6: Presentation layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.
    - Layer 7: Application layer. This is the layer that deals with the physical cables and devices that connect the computers to the network.

### The usage of AI

- To help me understand the concepts and how to use the network tools.
- To help me solve the exercises when I'm stuck.
- Proofreading this README.md file.

### References

- *マスタリングTCP/IP 入門編（第6版）*
- *CISCO: IP Addressing and Subnetting for New Users* Document ID: 13788
