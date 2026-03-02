# 🌐 Network Labs

> Practical network engineering labs documenting real-world experience
> from telecom production environments (Telefónica) and hands-on technical research.
> Built to support applications to Google SDE Edge Networking, NVIDIA Network SRE,
> and related roles.

---

## 🎯 Objective

Document and demonstrate deep networking knowledge across:

- **BGP / Internet Routing** — real ISP peering experience from Telefónica
- **LACP / Link Aggregation** — hands-on bonding configuration
- **PXE Boot** — network-based OS provisioning lab
- **Anycast / Edge CDN** — how Google Edge Network works
- **DNS Deep Dive** — resolution internals and troubleshooting
- **ISP Troubleshooting** — coordinating with carriers in production incidents

---

## 📁 Lab Index

| File                                                     | Topic                                              | Status         |
| -------------------------------------------------------- | -------------------------------------------------- | -------------- |
| [01-bgp-routing.md](./01-bgp-routing.md)                 | BGP concepts + Telefónica production cases         | 🔄 In progress |
| [02-lacp-bonding.md](./02-lacp-bonding.md)               | Link Aggregation lab on local VMs                  | ⏳ Planned     |
| [03-pxe-boot-lab.md](./03-pxe-boot-lab.md)               | PXE server with dnsmasq                            | ⏳ Planned     |
| [04-anycast-edge.md](./04-anycast-edge.md)               | Anycast routing + Google Edge Network architecture | ⏳ Planned     |
| [05-dns-deep-dive.md](./05-dns-deep-dive.md)             | DNS resolution internals + troubleshooting         | ⏳ Planned     |
| [06-isp-troubleshooting.md](./06-isp-troubleshooting.md) | Real ISP coordination cases from Telefónica        | ⏳ Planned     |

---

## 🛠️ Stack & Tools

- **OS:** Linux (Ubuntu 22.04 / CentOS)
- **Tools:** `tcpdump`, `traceroute`, `ip route`, `ss`, `netstat`, `iptables`, `dnsmasq`
- **Protocols:** BGP, TCP/IP, DNS, LACP (802.3ad), PXE/DHCP, VXLAN, VLAN
- **Cloud:** AWS VPC, GCP Networking
- **Automation:** Python, Bash, Ansible

---

## 👤 Background

**3+ years** of network operations experience at **Telefónica** (Venezuela), managing:

- BGP peering with upstream ISPs and regional carriers
- VLAN configuration and L2/L3 troubleshooting
- Coordinating remote incident resolution with ISP NOC teams
- TCP/IP stack diagnostics using `tcpdump`, `wireshark`, and custom tooling

Currently an **SRE at Trektel**, building toward roles at Google and NVIDIA
focused on network reliability and edge infrastructure.

---

## 🔗 Related Labs in this Repo

- [`/linux-internals`](../linux-internals/) — Linux kernel, filesystems, syscalls
- [`/sre-observability`](../sre-observability/) — Prometheus, Grafana, SLO engine
- [`/ci-cd-pipeline`](../ci-cd-pipeline/) — Jenkins, Groovy, ArgoCD
