# 🔧 SRE Labs

> Hands-on SRE and network engineering labs built to demonstrate production-level skills targeting roles at Google, and NVIDIA.

[![Certifications](https://img.shields.io/badge/Cert-Azure_Fundamentals-blue)](https://www.credly.com/badges/ad8fdfb1-6b65-48ac-a8cb-80f2d9fe372b/linked_in)
[![Target](https://img.shields.io/badge/Target-Google_SRE_%7C_NVIDIA-red)]()

## 🗂️ Lab Index

| Folder                                       | What it covers                                         | Target Role               |
| -------------------------------------------- | ------------------------------------------------------ | ------------------------- |
| [`/network-labs`](./network-labs/)           | Ethernet · TCP/IP · DNS · DHCP · VLANs · LACP · BGP · Anycast · VXLAN · PXE | G2 Google Edge Networking |
| [`/linux-internals`](./linux-internals/)     | Kernel, namespaces, cgroups, /proc, syscalls, boot     | G1, G2, A1                |
| [`/sre-observability`](./sre-observability/) | Prometheus, Grafana, Alertmanager, SLO Engine, OTel    | G1, A1, N1                |
| [`/ci-cd-pipeline`](./ci-cd-pipeline/)       | Jenkins + Groovy, ArgoCD, GitLab CI, Trivy             | A1 Arista                 |

## `/network-labs`

| Lab                                          | What it covers                                    | Level        |
| -------------------------------------------- | ------------------------------------------------- | ------------ |
| [`01-ethernet-fundamentals`](./network-labs/) | Ethernet frames, MAC, ARP, switching, VLANs       | Foundational |
| [`02-ip-subnetting`](./network-labs/)         | IPv4/IPv6, CIDR, subnetting, routing tables       | Foundational |
| [`03-tcp-ip-deep-dive`](./network-labs/)      | TCP handshake, UDP, sockets, Wireshark analysis    | Foundational |
| [`04-dns-dhcp-pxe`](./network-labs/)          | DNS resolution, DHCP leases, PXE boot lab          | Intermediate |
| [`05-vlan-trunking-lacp`](./network-labs/)    | 802.1Q, trunk ports, LACP bonding, STP             | Intermediate |
| [`06-routing-bgp`](./network-labs/)           | Static routes, OSPF basics, BGP peering, AS paths  | Advanced     |
| [`07-anycast-cdn-edge`](./network-labs/)      | Anycast routing, CDN architecture, edge networking  | Advanced     |
| [`08-network-troubleshooting`](./network-labs/) | tcpdump, traceroute, ss, iperf3, ISP escalation  | SRE Applied  |


## 🛠️ Core Stack

```
Languages:   Python · Go · Js/Ts · C/C++
Infra:       Kubernetes · Docker · Terraform · Ansible
Observ.:     Prometheus · Grafana · OpenTelemetry
Networking:  Ethernet · TCP/IP · DNS · DHCP · VLANs · LACP · BGP · Anycast · VXLAN · PXE
CI/CD:       Jenkins · ArgoCD · GitHub Actions · GitLab CI
Cloud:       AWS (EKS, VPC, IAM) · GCP (GKE)
Certs:       Azure Fundamentals → AWS SAA-C03 (in progress)
```

## 🎯 Target Roles (2026–2027)

| Role                          | Company              | Location     | Timeline     |
| ----------------------------- | -------------------- | ------------ | ------------ |
| SDE Edge Networking           | Google               | Sydney       | 3–5 months   |
| SWE I — SRE (G1)             | Google               | Sydney       | 4–6 months   |
| SRE — Technical Infra (JD Master) | Google           | Sydney       | 3–5 months   |
| Solutions Architect DevOps    | NVIDIA               | Sydney (Remote) | 10 months |
| Network SRE                   | NVIDIA               | Santa Clara  | 18–24 months |
| SRE HW Infrastructure        | NVIDIA               | Santa Clara  | 18–24 months |


## 📈 Progress

- [x] Repo created + structure defined
- [ ] `/network-labs` — Ethernet · TCP/IP · DNS · DHCP · VLANs · LACP · BGP · Anycast · VXLAN · PXE
- [ ] `/linux-internals` — kernel lab
- [ ] `/sre-observability` — P1 Observability Platform
- [ ] `/ci-cd-pipeline` — Jenkins Framework
- [ ] AWS SAA-C03 exam
- [ ] First technical post in English (LinkedIn)

## 📬 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fernando_Hernández-blue)](https://www.linkedin.com/in/fernandoh/)
