# 🌐 Network Labs

> Progressive network engineering labs — from Ethernet fundamentals to production ISP troubleshooting.
> Built on real-world experience from telecom environments (Telefónica) and hands-on research.
> Targeting: Google SDE Edge Networking, Google SRE, NVIDIA Solutions Architect DevOps.
---

## 🎯 Objective

Build a complete networking knowledge path demonstrating:

- **Layer 1–2 Fundamentals** — Ethernet, switching, VLANs, link aggregation
- **Layer 3–4 Protocols** — IP, TCP/UDP, routing, subnetting
- **Core Services** — DNS, DHCP, PXE boot
- **Internet Routing** — BGP peering, AS paths, OSPF (real ISP experience from Telefónica)
- **Edge & CDN** — Anycast routing, Google Edge Network architecture
- **SRE Applied** — production troubleshooting, ISP coordination, packet analysis

---
## 📁 Lab Index

### Foundational

| Lab | Topic | Tools | Status |
| --- | ----- | ----- | ------ |
| [`01-ethernet-fundamentals`](./01-ethernet-fundamentals.md) | Ethernet frames, MAC addressing, ARP, switching, broadcast domains | Wireshark, tcpdump | ⏳ Planned |
| [`02-ip-subnetting`](./02-ip-subnetting.md) | IPv4/IPv6, CIDR notation, subnetting, routing tables | ipcalc, ip route | ⏳ Planned |
| [`03-tcp-ip-deep-dive`](./03-tcp-ip-deep-dive.md) | TCP handshake, UDP, sockets, window sizing, Wireshark analysis | Wireshark, ss, netstat | ⏳ Planned |

### Intermediate

| Lab | Topic | Tools | Status |
| --- | ----- | ----- | ------ |
| [`04-dns-dhcp`](./04-dns-dhcp.md) | DNS resolution internals, DHCP leases, troubleshooting | dnsmasq, dig, nslookup | ⏳ Planned |
| [`05-pxe-boot-lab`](./05-pxe-boot-lab.md) | PXE server setup, network-based OS provisioning | dnsmasq, tftp, Wireshark | ⏳ Planned |
| [`06-vlan-trunking-lacp`](./06-vlan-trunking-lacp.md) | 802.1Q VLANs, trunk ports, LACP bonding (802.3ad), STP | ip link, bridge, nmcli | ⏳ Planned |

### Advanced

| Lab | Topic | Tools | Status |
| --- | ----- | ----- | ------ |
| [`07-routing-bgp`](./07-routing-bgp.md) | Static routes, OSPF basics, BGP peering, AS paths + Telefónica production cases | FRRouting, ip route, traceroute | 🔄 In progress |
| [`08-anycast-cdn-edge`](./08-anycast-cdn-edge.md) | Anycast routing, CDN architecture, Google Edge Network | traceroute, dig, mtr | ⏳ Planned |

### SRE Applied

| Lab | Topic | Tools | Status |
| --- | ----- | ----- | ------ |
| [`09-network-troubleshooting`](./09-network-troubleshooting.md) | tcpdump analysis, traceroute debugging, iperf3, packet diagnosis | tcpdump, ss, iperf3, mtr | ⏳ Planned |
| [`10-isp-troubleshooting`](./10-isp-troubleshooting.md) | Real ISP coordination cases from Telefónica, NOC escalation procedures | tcpdump, traceroute, mtr | ⏳ Planned |

---

## 🛠️ Stack & Tools

- **OS:** Linux (Ubuntu 22.04 / CentOS)
- **Tools:** `tcpdump`, `traceroute`, `ip route`, `ss`, `netstat`, `iptables`, `dnsmasq`, `Wireshark`, `dnsmasq`, `mtr`
- **Protocols:** Ethernet · TCP/IP · DNS · DHCP · VLANs · LACP · BGP · Anycast · VXLAN · PXE
- **Cloud:** AWS VPC · GCP Networking
- **Automation:** Python, Bash, Ansible

---

Currently an **SRE at Trektel**. 
Bilding toward roles at Google and NVIDIA
Focused on network reliability and edge infrastructure.

---

## 🔗 Related Labs

- [`/linux-internals`](../linux-internals/) — Kernel, namespaces, cgroups, syscalls
- [`/sre-observability`](../sre-observability/) — Prometheus, Grafana, SLO engine
- [`/ci-cd-pipeline`](../ci-cd-pipeline/) — Jenkins, Groovy, ArgoCD
