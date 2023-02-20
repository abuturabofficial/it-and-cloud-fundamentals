<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Hardware, Network Flow, and Protocols](#hardware-network-flow-and-protocols)
  - [Networking Hardware Devices](#networking-hardware-devices)
    - [Network Devices](#network-devices)
    - [What is a server?](#what-is-a-server)
      - [What are nodes and clients?](#what-are-nodes-and-clients)
      - [Client-server](#client-server)
      - [Peer-to-peer](#peer-to-peer)
      - [Hubs and Switches](#hubs-and-switches)
      - [Routers and modems](#routers-and-modems)
      - [Bridges and gateways](#bridges-and-gateways)
      - [Repeaters and WAPs](#repeaters-and-waps)
      - [Network Interface Cards (NICs)](#network-interface-cards-nics)
      - [Firewalls, proxies, IDS, and IPS](#firewalls-proxies-ids-and-ips)
  - [Packets, IP Addressing, DNS, DHCP, and NAT](#packets-ip-addressing-dns-dhcp-and-nat)
    - [What is a packet?](#what-is-a-packet)
    - [Data Transmission Flow Types](#data-transmission-flow-types)
    - [IP Packets Transmission Modes](#ip-packets-transmission-modes)
    - [Data Transmission Flow](#data-transmission-flow)
    - [IPv4 and IPv6](#ipv4-and-ipv6)
      - [What is an IP address?](#what-is-an-ip-address)
      - [IP Address Types](#ip-address-types)
    - [DNS](#dns)
    - [Dynamic Host Configuration Protocol (DHCP)](#dynamic-host-configuration-protocol-dhcp)
    - [Subnetting (and Subnet Mask)](#subnetting-and-subnet-mask)
    - [Automatic Private IP Addressing (APIPA)](#automatic-private-ip-addressing-apipa)
    - [Network Address Translation (NAT)](#network-address-translation-nat)
    - [Media Access Control (MAC) Addresses](#media-access-control-mac-addresses)
  - [Models, Standards, Protocols, and Ports](#models-standards-protocols-and-ports)
    - [Networking Models](#networking-models)
      - [7 Layer OSI Model](#7-layer-osi-model)
      - [5 Layer TCP/IP Model](#5-layer-tcpip-model)
    - [Network Standards and their Importance](#network-standards-and-their-importance)
      - [Noted Network Standards Organizations](#noted-network-standards-organizations)
    - [Protocols](#protocols)
      - [Protocols – TCP vs. UDP](#protocols--tcp-vs-udp)
      - [Protocols – TCP/IP](#protocols--tcpip)
      - [Protocols – Internet of Things](#protocols--internet-of-things)
      - [Protocols – Crypto Classic](#protocols--crypto-classic)
    - [Commonly Used Ports](#commonly-used-ports)
  - [Wireless Networks and Standards](#wireless-networks-and-standards)
    - [Network types](#network-types)
      - [WPAN](#wpan)
      - [WLAN](#wlan)
      - [WMAN](#wman)
      - [WWAN](#wwan)
      - [Wireless ad hoc network](#wireless-ad-hoc-network)
    - [Cellular networks](#cellular-networks)
      - [IEEE 802.20 and IEEE 802.22](#ieee-80220-and-ieee-80222)
  - [Protocol Table](#protocol-table)
    - [Web page protocols](#web-page-protocols)
    - [File transfer protocols](#file-transfer-protocols)
    - [Remote access protocols](#remote-access-protocols)
    - [Email protocols](#email-protocols)
    - [Network Protocols](#network-protocols)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Hardware, Network Flow, and Protocols

## Networking Hardware Devices

### Network Devices

Network devices, or networking hardware, enable communication and interaction on a computer network.

This includes:
- Cables
- Servers
- Desktops
- Laptops
- Tablets
- Smartphones
- IoT devices

### What is a server?

- Other computers or devices on the same network can access the server
- The devices that access the server are known as clients
- A user can access a server file or application from anywhere

#### What are nodes and clients?

A node is a network-connected device that can send and receive information.
- All devices that can send, receive, and create information on a network are nodes.
- The nodes that access servers to get on the network are known as clients.

#### Client-server

Client-server networks are common in businesses.
- They keep files up-to-date
- Easy-to-find
- One shared file in one location

Examples of services that use client-server networks:
- FTP sites
- Web servers
- Web browsers

#### Peer-to-peer

Peer-to-peer networks are common in homes on the Internet.

Examples:
- File sharing sites
- Discussion forums
- Media streaming
- VoIP services

#### Hubs and Switches

**A hub:**
- Connects multiple devices together
- Broadcasts to all devices except sender

**A switch:**
- Keeps a table of MAC addresses
- Sends directly to correct address (More efficient than hubs)

#### Routers and modems

Routers interconnect different networks or subnetworks.
- Manage traffic between networks by forwarding data packets
- Allow multiple devices to use the same Internet connection

Routers use internal routing to direct packets effectively
The router:
- Reads a packet's header to determine its path
- Consults the routing table
- Forwards the packet

A modem converts data into a format that is easy to transmit across a network.
- Data reaches its destination, and the modem converts it to its original form
- Most common modems are cable and DSL modems

#### Bridges and gateways

A **bridge** joins two separate computer networks, so they can communicate with each other and work as a single network.

Wireless bridges can support:
- Wi-Fi to Wi-F i
- Wi-Fi to Ethernet
- Bluetooth to Wi-Fi

A **gateway** is a hardware or software that allows data to flow from one network to another, for examples, a home network to the Internet.

![](images/Pasted%20image%2020230220114524.png)

#### Repeaters and WAPs

**Repeaters**
- Receive a signal and retransmits it
- Used to extend a wireless signal
- Connect to wireless routers

**Wireless Access Point (WAP)**
- Allows Wi-Fi devices to connect to a wired network
- Usually connects to a wired router as a standalone device
- Acts as a central wireless connection point for computers equipped with wireless network adapters

#### Network Interface Cards (NICs)

NICs connect individual devices to a network.

![](images/Pasted%20image%2020230220114903.png)

#### Firewalls, proxies, IDS, and IPS

A **firewall** monitors and controls incoming and outgoing network traffic based on predetermined security rules.
- Firewalls can be software or hardware
- Routers and operating systems have built-in firewalls

![](images/Pasted%20image%2020230220115122.png)

**A Proxy Server:**
- Works to minimize security risks
- Evaluates requests from clients and forwards them to the appropriate server
- Hides an IP address
- Saves bandwidth

**IDS and IPS:**
- IDS monitors network traffic and reports malicious activity
- IPS inspects network traffic and removes, detains, or redirects malicious items

![](images/Pasted%20image%2020230220115305.png)

## Packets, IP Addressing, DNS, DHCP, and NAT

### What is a packet?

Everything you do on the Internet involves packets.

Packets are also called:
- Frames
- Blocks
- Cells
- Segments

### Data Transmission Flow Types

![](images/Pasted%20image%2020230220120541.png)

### IP Packets Transmission Modes

![](images/Pasted%20image%2020230220120709.png)

### Data Transmission Flow

When you send an email, it is broken down into individually labeled data packets and sent across the network.

### IPv4 and IPv6

- IPv4 is one of the core protocols for the Internet.
- IPv6 is the newest version of Internet Protocol.

#### What is an IP address?

An IP address is used to logically identify each device (Host) on a given network.

![](images/Pasted%20image%2020230220121114.png)

#### IP Address Types

**Static**: Static IP addresses are manually assigned.

**Dynamic:** Dynamic IP addresses are automatically assigned.

**Public:** Public IP address is used to communicate publically.

**Private:** Private IP address is used to connect securely within an internal, private network.

**Loopback:** Loopback is the range of IP addresses reserved for the local host.

**Reserved:** Reserved IP addresses have been reserved by the **IETF and IANA**.

### DNS

The DNS is the phone book of the internet.

![](images/Pasted%20image%2020230220121613.png)

### Dynamic Host Configuration Protocol (DHCP)

The DHCP automates the configuring of IP network devices.

A DHCP server uses a pool of reserved IP addresses to automatically assign dynamic IP addresses or allocate a permanent IP address to a device.

**Static allocation:**
The server uses a manually assigned “permanent” IP address for a device.

**Dynamic allocation:**
The server chooses which IP address to assign a device each time it connects to the network.

**Automatic allocation:**
The server assigns a “permanent” IP addresses for a device automatically.

### Subnetting (and Subnet Mask)

Subnetting is the process of taking a large, single network and splitting it up into many individual smaller subnetworks or subnets.
- Identifies the boundary between the IP network and the IP host.
- Internal usage within a network.
- Routers use subnet masks to route data to the right place.

![](images/Pasted%20image%2020230220122124.png)

### Automatic Private IP Addressing (APIPA)

APIPA is a feature in operating systems like Windows that let computers self-configure an IP address and subnet mask automatically when the DHCP server isn’t reachable.

![](images/Pasted%20image%2020230220122413.png)

### Network Address Translation (NAT)

NAT is a process that maps multiple local private addresses to a public one before transferring the information.
- Multiple devices using a single IP address
- Home routers employ NAT
- Conserves public IP addresses
- Improves security

**NAT instructions send all data packets without revealing private IP addresses of the intended destination.**

![](images/Pasted%20image%2020230220122538.png)

### Media Access Control (MAC) Addresses

A MAC address is the physical address of each device on a network.

![](images/Pasted%20image%2020230220122902.png)

## Models, Standards, Protocols, and Ports

### Networking Models

A networking model describes:
- Architecture
- Components
- Design

Two types:
1) OSI Model
A conceptual framework used to describe the functions of a networking system.
2) TCP/IP Model
A set of standards that allow computers to communicate on a network. TCP/IP is based on the OSI model.

#### 7 Layer OSI Model

![](images/Pasted%20image%2020230220123353.png)

#### 5 Layer TCP/IP Model

The TCP/IP model is a set of standards that allow computers to communicate on a network. TCP/IP is based on the OSI model.

![](images/Pasted%20image%2020230220135436.png)

### Network Standards and their Importance

Networking standards define the rules for data communications that are needed for interoperability of networking technologies and processes.

There are two types of network standards:
1) De-jure or Formal Standards
Developed by an official industry or government body.

**Examples:** HTTP, HTML, IP, Ethernet 802.3d

2) De-Facto Standards
De-facto standards result from marketplace domination or practice.

**Examples:** Microsoft Windows, QWERTY keyboard

#### Noted Network Standards Organizations

Standards are usually created by government or non-profit organizations for the betterment of an entire industry.

1) **ISO:** Established the well known OSI reference networking model.
2) **DARPA:** Established the TCP/IP protocol suit.
3) **W3C:** Established the World Wide Web (WWW) standard.
4) **ITU:** Standardized international telecom, set standards for fair use of radio frequency.
5) **IEEE:** Established the IEEE 802 standards.
6) **IETF:** Maintains TCP/IP protocol suites. IETF also developed RFC standard.

### Protocols

A network protocol is a set of rules that determines how data is transmitted between different devices in the same network.

1) Security
	- Encryption
	- Authentication
	- Transportation
2) Communication
	- Encryption
	- Authentication
	- Transportation
3) Network Management
	- Connection
	- Link Aggregation
	- Troubleshooting

#### Protocols – TCP vs. UDP

| TCP                       | UDP                        |
| ------------------------- | -------------------------- |
| Slower but more reliable  | Faster but not guaranteed  |
| Typical applications      | Typical application        |
| 1) File transfer protocol | 1) Online games            |
| 2) Web browsing           | 2) Calls over the internet | 
| 3) EMAIL                  |                            |

#### Protocols – TCP/IP

The TCP/IP suite is a collection of protocols.

![](images/Pasted%20image%2020230220141237.png)

#### Protocols – Internet of Things

![](images/Pasted%20image%2020230220141335.png)

#### Protocols – Crypto Classic

The Crypto Classic protocol is designed to serve as one of the most efficient, effective, and secure payment methods built on the blockchain network.

**Bitcoin Protocol:** A peer-to-peer network operating on a cryptographic protocol used for bitcoin transactions and transfers on the Internet.

**Blockchain Protocol:** An open, distributed ledger that can record transactions between two parties efficiently and in a verifiable and permanent way.

### Commonly Used Ports

Ports are the first and last stop for information sent across a network.
- A port is a communication endpoint.
- A port always has an associated protocol and application.
- The protocol is the path that leads to the application’s port.
- A network device can have up to **65536** ports.
- Port numbers do not change.

![](images/Pasted%20image%2020230220141814.png)

## Wireless Networks and Standards

### Network types

![](images/Pasted%20image%2020230220142239.png)

#### WPAN

A WPAN connects devices within the range of an individual person (10 meters). WPANs use signals like **infrared, Zigbee, Bluetooth, and ultra-wideband**.

![](images/Pasted%20image%2020230220142521.png)

#### WLAN

A WLAN connects computers and devices within homes, offices, or small businesses. WLANs use Wi-Fi signals from routers, modems, and wireless access points to wirelessly connect devices.

![](images/Pasted%20image%2020230220142715.png)

#### WMAN

A WMAN spans a geographic area (size of a city). It serves ranges greater than 100 meters.

![](images/Pasted%20image%2020230220142836.png)

#### WWAN

A WWAN provides regional, nationwide, and global wireless coverage. This includes private networks of multinational corporations, **the Internet, and cellular networks like 4G, 5G, LTE, and LoRaWAN**.

![](images/Pasted%20image%2020230220143103.png)

#### Wireless ad hoc network

A WANET uses Wi-Fi signals from whatever infrastructure happens to be available to connect devices instantly, anywhere. WANETs are similar in size to WLANs, but use technology that is closer to WWANs and cellular network.

**Advantages:**
- Flexible
- No required infrastructure
- Can be set up anywhere instantly

**Disadvantages:**
- Limited bandwidth quality
- Not robust
- Security risks

![](images/Pasted%20image%2020230220143513.png)

### Cellular networks

A cellular network provides regional, nationwide, and global mesh coverage for mobile devices.

![](images/Pasted%20image%2020230220143654.png)

**Advantages**
- Flexibility
- Access
- Speed and efficiency

**Disadvantages**
- Expensive
- Decreased coverage
- Hardware limitations

#### IEEE 802.20 and IEEE 802.22

The IEEE 802.20 and 802.22 standards support WWANs, cellular networks and WANETs.

![](images/Pasted%20image%2020230220144006.png)

**IEEE 802.20**
- Optimizes bandwidth to increase coverage or mobility
- Used to fill the gap between cellular and other wireless networks

**IEEE 802.22**
- Uses empty spaces in the TV frequency spectrum to bring broadband to low-population, hard-to-reach areas

## Protocol Table

### Web page protocols

![](images/Pasted%20image%2020230220144447.png)

### File transfer protocols

![](images/Pasted%20image%2020230220144529.png)

### Remote access protocols

![](images/Pasted%20image%2020230220144628.png)

### Email protocols

![](images/Pasted%20image%2020230220145255.png)

### Network Protocols

![](images/Pasted%20image%2020230220145427.png)
