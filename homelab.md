---
layout: page
title: Homelab
permalink: /homelab/
---

# My Homelab Setup

I use a Dell PowerEdge R730 to run all my cybersecurity and networking labs.

## Server Specs

- **Model:** Dell PowerEdge R730
- **CPU:** Dual Intel Xeon E5-2630 V4
- **Memory:** 64GB DDR4-2133 ECC
- **Storage:**
	- 2x 300GB 12K SAS (OS)
	- 12x 1.2TB 10k SAS (Storage / Backups)
- **Hypervisor:** Proxmox VE
- **Networking:** Cisco Catalyst 3750G 48PS Switch

## Network Topology

*Diagram coming soon!*
I will be working on this shortly, so for now this is just a placeholder!

## Projects and Experiments

These are some planned projects that I will be running on my homelab:

- **Active Directory Lab:** Windows Server + Linux clients for defensive testing.
- **Centralized Logging:** Using Splunk to collect logs from servers, firewalls, lab VMs, etc.
- **Firewall and IDS/IPS:** pfSense + Suricata/Snort for intrusion detection and network security.
- **Penetration Testing:** Kali Linux VM for penetration testing simulations.
- **Automation Scripts:** Python scripts for logging and parsing data, creating alerts, and various monitoring tasks.

## Notes and Best Practices

- I always **isolate attack networks** from my main homelab to prevent accidental contamination
- Keep snapshots/backups for quick recovery after experiments
- Document everything - helps with both learning and provide portfolio content