# \# Home Security Lab — SIEM Intrusion Detection

# 

# Virtualized cybersecurity lab simulating real attacks and detecting

# them with Wazuh SIEM. Part of my cybersecurity portfolio.

# 

# \## Lab Architecture

# | Machine | OS | Role | IP |

# |---|---|---|---|

# | Kali Linux | Kali 2024 | Attacker | 192.168.56.1 |

# | Windows Server | Server 2019 | Target | 192.168.56.102 |

# | Ubuntu + Wazuh | Ubuntu 22.04 | SIEM | 192.168.56.104 |

# 

# \## Attack Scenarios Simulated

# 1\. Network reconnaissance — Nmap -sV -sC scan

# 2\. Brute force authentication — Hydra against RDP

# 

# \## Key Detections

# \- Port scan detected (ports 135, 139, 445, 3389, 5985)

# \- NTLM authentication attempts from Kali detected

# \- Multiple authentication failures logged

# 

# \## Screenshots

# !\[Wazuh Alerts](screenshots/wazuh-alerts.png)

# !\[Alert Detail](screenshots/alert-detail.png)

# !\[Agent Active](screenshots/agent-active.png)

# 

# \## Tools Used

# \- VirtualBox 7.x

# \- Wazuh 4.9 (SIEM)

# \- Nmap 7.x

# \- Hydra

# \- Kali Linux 2024

# 

# \## Skills Demonstrated

# \- SIEM deployment and configuration

# \- Network attack simulation in controlled environment

# \- Alert analysis and log correlation

# \- Security monitoring and incident detection

# 

# \*Juan Esteban Umana Machado — linkedin.com/in/juanesumaa11\*

