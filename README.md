<div align="center">

# `0xEmhddsi-Net`

**Systems & Network Administration** · **Cyber Defense** · **Zero Trust**

*Building secure, segmented, auditable infrastructure, one lab at a time.*

![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-C8202F?style=for-the-badge&logo=comptia&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Cyber_Defense-0A1F44?style=for-the-badge)
![Labs](https://img.shields.io/badge/Method-Hands--on_Labs-2E7D32?style=for-the-badge)

</div>

---

```bash
$ whoami
0xEmhddsi-Net

$ cat about.txt
Sysadmin foundations (Windows Server, Linux, networking)
+ a defender's mindset (PAM, NGFW, EDR, SIEM, MFA)
= infrastructure that is segmented, encrypted and auditable.

$ cat principles.txt
never trust, always verify
least privilege, always
if it isn't logged, it didn't happen
document everything, break it on purpose, fix it, repeat
```

---

## 🔭 What I work on

- 🛡️ **Privileged Access Management and Zero Trust**: brokering every admin session through a bastion
- 🔐 **Identity and encrypted auth**: Active Directory, LDAPS, PKI
- 🧱 **Network segmentation**: VLANs, isolated zones, firewalls
- 🕵️ **Detection and response labs**: attack simulation (Red vs Blue) and SIEM monitoring
- 🐧 **Linux and virtualization**: Debian, Proxmox VE, VMware

---

## 📌 Featured project

<table>
<tr>
<td width="70%">

### 🏰 [Zero Trust Architecture with WALLIX Bastion (PAM)](https://github.com/0xEmhddsi-Net/Architecture-Zero-Trust-Wallix-Bastion-PAM)

A zero-trust lab where **nobody touches a target directly**. All access is brokered, authenticated and audited through a PAM bastion.

`RDP → Windows Server` · `RDS → Chrome RemoteApp` · `SSH → Debian` · `LDAPS (636), not LDAP`

Isolated network zones, separated admin and user planes, AD + PKI, and a full step-by-step screenshot walkthrough.

</td>
<td>

```mermaid
flowchart TB
    U["User"] --> B["PAM Bastion"]
    B --> W["Windows (RDP)"]
    B --> C["Chrome (RDS)"]
    B --> D["Debian (SSH)"]
    B -.->|LDAPS| AD["Active Directory"]
```

</td>
</tr>
</table>

---

## 🧪 Labs

| Lab | What it covers |
|---|---|
| 🏢 **Hybrid Enterprise** | Proxmox + Cisco VLAN architecture. An isolated "virtual cage" bridge to air-gap the lab and stop DHCP leaks. Windows Server (AD/DHCP) and pfSense |
| ⚔️ **SIEM Attack Detection (Red vs Blue)** | Attacks from Kali (Nmap, brute force) detected and analysed in a SIEM, plus CLI troubleshooting (`fdisk`, `growpart`, swap) |
| 🏰 **Zero Trust PAM** | See the featured project above |

---

## 🧰 Toolbox

| Area | Tech |
|---|---|
| **Access and identity** | WALLIX Bastion · Active Directory · GPO · LDAPS · PKI (AD CS) · MFA |
| **Network security** | Palo Alto NGFW · pfSense · Barracuda WAF · Forcepoint SWG · FortiNAC |
| **Endpoint and data** | Kaspersky EDR · Tripwire (FIM) · PGP encryption |
| **Monitoring and offense** | Splunk · Kali Linux · Nmap |
| **Systems** | Windows Server · Debian Linux · Proxmox VE · VMware Workstation |
| **Networking** | TCP/IP · VLAN · DNS · DHCP · SSH · Cisco |

---

## 🎓 Certifications

- ✅ **CompTIA Security+**
- ✅ **Cyber Defense Administrator**, program certificate
- 📘 **Linux Unhatched** (Cisco)

---

## 🎯 Currently

- 🔨 Writing up labs as clean, reproducible documentation
- 📚 Going deeper on detection engineering and SIEM use cases
- 🧭 Looking for a junior role in **systems administration or cyber defense**

---

<div align="center">

*"The best way to learn security is to build it, break it, and write it down."*

</div>
