# Wazuh SIEM Home Lab: Attack and Detect

A hands-on SOC detection lab where I built a small SIEM environment, simulated attacks against it, and validated the alerts in Wazuh.

## Lab Overview

| Component | Details |
|---|---|
| Hypervisor | VirtualBox |
| SIEM server | Ubuntu running Wazuh (all-in-one) |
| Attacker | Kali Linux |
| Network | Host-only network |

## What I Did

- Set up a two-VM lab with Wazuh as the monitoring server and Kali as the attacker
- Ran **Nmap** reconnaissance against the target
- Generated **SSH failed-login** events
- Simulated an SSH **brute-force attack with Hydra**
- Confirmed detections in the **Wazuh dashboard** and in `alerts.log`

## Skills Demonstrated

SIEM deployment, log monitoring, alert analysis, network reconnaissance, brute-force detection, Linux administration, and technical documentation.

## Documents in This Repo

| File | Description |
|---|---|
| `Wazuh-Lab-Portfolio-Writeup` (.docx / .pdf) | Project summary for portfolio use |
| `Wazuh-Lab-Blog-Writeup` (.docx / .pdf) | Beginner-friendly step-by-step walkthrough |

## Disclaimer

All testing was done in an isolated, self-owned lab environment for educational purposes only.

## Author

**Rina Aranas**: aspiring SOC Analyst, working toward CompTIA Security+
Portfolio: https://portfolio.rinaaranas.site | GitHub: [@thesunnymc](https://github.com/thesunnymc)
