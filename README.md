# 🧪 Home Lab – Ethical Hacking & Cloud Security Practice

This repository documents my hands-on cybersecurity practice using a self-built home lab. The goal of this lab is to reinforce ethical hacking, network analysis, and cloud security concepts in a safe, isolated environment.

---

## 🖥️ Lab Environment

- **Virtualization Platform**: Oracle VirtualBox
- **Operating Systems**:
  - Kali Linux (attacker VM)
  - Metasploitable2 / DVWA (target VMs)
  - Windows 10 test machine
- **Network Setup**: Host-only adapter with isolated virtual network

---

## 🔧 Tools Practiced

| Tool        | Purpose                                      |
|-------------|----------------------------------------------|
| **Nmap**     | Network and port scanning                    |
| **Burp Suite** | Web application interception and testing    |
| **Wireshark** | Network traffic capture and protocol analysis |
| **Metasploit** | Exploit development and testing             |

---

## 🧪 Sample Practice Scenarios

### 🔍 Nmap Scan – Network Discovery
```bash
nmap -sS -sV 192.168.56.0/24
