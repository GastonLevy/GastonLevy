# Hi, I'm Gastón Levy 👋

### Network & Infrastructure Engineer | Linux • Python • MikroTik • Cisco Networking

I'm a Network and Infrastructure Engineer based in **Vienna, Austria**, with hands-on experience operating ISP and enterprise network infrastructure.

My main interests are **Linux networking, routing & switching, network automation, infrastructure monitoring and Python tooling**.

I enjoy understanding how networks work below the abstraction layer — from routing tables, interfaces and firewall state to Linux kernel networking APIs — and building tools that make infrastructure easier to inspect, automate and operate.

Currently studying for the **Cisco CCNA** and developing **OpenJoaju**, an open-source Linux networking project.

---

## 🚀 Current Focus

* Linux Networking
* Python for Network Engineering
* Netlink / rtnetlink
* Routing & Switching
* Cisco CCNA
* MikroTik RouterOS
* nftables / Linux Firewalling
* DHCP & DNS
* Network Automation
* Infrastructure Monitoring

---

## 🌐 Networking

![Linux Networking](https://img.shields.io/badge/Linux-Networking-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Cisco](https://img.shields.io/badge/Cisco-Networking-1BA0D7?style=for-the-badge\&logo=cisco\&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-RouterOS-293239?style=for-the-badge\&logo=mikrotik\&logoColor=white)
![TCP/IP](https://img.shields.io/badge/TCP%2FIP-Networking-005571?style=for-the-badge)
![OSPF](https://img.shields.io/badge/OSPF-Routing-005571?style=for-the-badge)
![VLAN](https://img.shields.io/badge/VLAN-Switching-005571?style=for-the-badge)

### Networking Experience

* Routing & Switching
* VLANs and trunking
* STP / RSTP
* OSPF
* Static and recursive routing
* NAT / PAT / CGNAT
* ACLs
* DHCP
* DNS
* VPNs
* MikroTik RouterOS
* FTTH / GPON infrastructure
* Network monitoring and troubleshooting

---

## 🐧 Linux & Network Automation

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge\&logo=debian\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge\&logo=linux\&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge\&logo=gnubash\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)

I'm particularly interested in working directly with native Linux networking facilities such as:

* Netlink / rtnetlink
* Netfilter Netlink
* Linux sockets
* `/proc`
* `/sys`
* nftables
* Network namespaces
* Linux routing tables

---

# ⭐ Featured Project

## 🐧 OpenJoaju

**Lightweight, modular Linux network management.**

OpenJoaju is an open-source project written primarily in **Python** for inspecting and monitoring Linux networking without replacing the native Linux networking stack.

Linux remains the source of truth.

OpenJoaju communicates with native Linux interfaces to build structured representations of the current network state.

### Currently implemented

#### Network Interfaces

* Interface discovery
* IPv4 / IPv6 addresses
* MAC addresses
* MTU
* Link state
* Carrier state
* Link speed and duplex
* RX / TX statistics
* Real-time interface monitoring
* In-memory state tracking

#### Routing

* IPv4 and IPv6 routes
* Multiple routing tables
* Gateways
* Metrics
* Route protocols
* Route scopes and types
* Multipath routes
* Real-time route monitoring

#### Linux Firewall

* nftables tables
* Chains
* Rules
* Structured rule expressions
* Netfilter Netlink communication
* Real-time firewall state monitoring

OpenJoaju prefers **native kernel interfaces and event-driven monitoring** instead of parsing CLI output or continuously polling the system.

### Architecture

```text
                    OpenJoaju
                        │
                 Presentation
                        │
                  Module State
                        │
              Discovery + Monitoring
                        │
        ┌───────────────┼───────────────┐
        │               │               │
     Netlink          /proc            /sys
        │               │               │
        └───────────────┼───────────────┘
                        │
                     Linux
```

➡️ **Repository**

https://github.com/GastonLevy/OpenJoaju

---

# 🔧 Other Infrastructure Projects

## OpenTaragui

Backend platform for managing **MikroTik devices and ISP infrastructure**.

Built with ASP.NET Core and designed around network infrastructure management.

### Highlights

* MikroTik RouterOS REST API
* Network device management
* REST API
* Encrypted router credentials
* MySQL
* Entity Framework Core
* Integration testing
* Testcontainers
* Docker

➡️ **Repository**

https://github.com/GastonLevy/OpenTaragui

---

## 🌐 Beruki

Open-source ISP management platform.

Built around managing customers and network infrastructure in MikroTik-based ISP environments.

Technologies include:

* MikroTik integration
* Angular
* Symfony
* Docker
* JWT Authentication
* MySQL

---

# 🏗 Infrastructure & Operations

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge\&logo=docker\&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge\&logo=nginx\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge\&logo=githubactions\&logoColor=white)

Experience working with:

* Linux servers
* Docker
* Nginx
* Virtual machines
* Network monitoring
* Infrastructure troubleshooting
* MikroTik infrastructure
* ISP environments

---

## 💻 Software Development

Software development is another tool I use to solve infrastructure and networking problems.

I also have experience with:

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge\&logo=csharp\&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge\&logo=.net\&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge\&logo=angular\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge\&logo=typescript\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)

My development background helps me build **network automation tools, infrastructure APIs and operational software** rather than treating networking and software as separate areas.

---

# 📫 Contact

🌐 **Portfolio**
https://gastonlevy.com

💼 **LinkedIn**
https://linkedin.com/in/gaston-omar-lino-levy

📧 **Email**
[ggastlino@gmail.com](mailto:ggastlino@gmail.com)
