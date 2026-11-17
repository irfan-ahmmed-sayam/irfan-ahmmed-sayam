import pypandoc

readme = r'''<div align="center">

# Hi, I'm Irfan Ahmmed Sayam 👋

### Network & System Engineer | Networking | Windows Server | MikroTik | Linux

<p>
  <a href="https://github.com/irfan-ahmmed-sayam">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github" alt="GitHub">
  </a>
  <a href="https://www.linkedin.com/in/irfan-ahmmed-sayam">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://www.youtube.com/@themeaningofn">
    <img src="https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube" alt="YouTube">
  </a>
  <a href="https://www.facebook.com/irfan.ahmmed.sayam">
    <img src="https://img.shields.io/badge/Facebook-Connect-0866FF?style=for-the-badge&logo=facebook" alt="Facebook">
  </a>
</p>

📍 Dhaka, Bangladesh

</div>

---

## 👨‍💻 About Me

I am a Network & System Engineer with practical learning experience in networking, infrastructure, and server administration. I enjoy building hands-on lab environments, documenting configurations, troubleshooting technical issues, and continuously improving my skills.

My current technical focus areas are **Networking (CCNA), Windows Server, MikroTik, and Linux Server Administration**. I am interested in **NOC and System Administration** roles where I can apply my knowledge, solve real-world technical problems, and continue developing professionally.

- 🌐 Learning and practicing enterprise networking concepts.
- 🖥️ Building Windows Server lab environments and documenting configurations.
- 📡 Practicing MikroTik RouterOS and network infrastructure concepts.
- 🐧 Developing my Linux administration skills.
- 📝 Sharing practical labs, notes, and learning progress on GitHub and YouTube.

## 🛠️ Technical Skills

### Networking
- CCNA Fundamentals
- Routing & Switching
- VLAN Segmentation and Inter-VLAN Routing
- OSPF and BGP Fundamentals
- GRE VPN
- NAT/PAT and ACL
- IPv4/IPv6 Subnetting
- SSH and Network Troubleshooting

### Windows Server Administration
- Windows Server 2016, 2019, and 2022
- Active Directory Domain Services (AD DS)
- Domain Controller and Additional Domain Controller
- DNS and DHCP
- Group Policy (GPO) and Organizational Units (OU)
- Remote Desktop (RDP) Configuration
- SMB File Sharing and Identity Management

### MikroTik & ISP Infrastructure
- MikroTik RouterOS
- Queues and Bandwidth Management
- OLT and ONU Systems
- Network Diagnostics
- Infrastructure Troubleshooting

### Linux & Operating Systems
- Linux Fundamentals and Administration
- Ubuntu
- CentOS
- Kali Linux

### Tools & Platforms
- Cisco Packet Tracer
- VMware Workstation
- Git and GitHub
- Microsoft Office

### Programming Fundamentals
- C
- C++
- Java
- JavaScript

## 🚀 Projects & Practical Labs

### 1. IAS Limited – Multi-Branch WAN Architecture
**Tools:** Cisco Packet Tracer

Designed a three-branch enterprise network representing Dhaka, Cumilla, and Chattogram.

- Implemented VLAN segmentation, inter-VLAN routing, DHCP, and NAT/PAT.
- Connected branches using eBGP between ISPs and hub-and-spoke GRE tunnels with multi-area OSPF.
- Configured SSH v2 for remote router access and ACLs to protect the IT VLAN.

🔗 **Project Repository:** [IAS Limited Multi-Branch WAN Architecture](https://github.com/irfan-ahmmed-sayam/ias-limited-multi-branch-wan-architecture)

### 2. Windows Server Infrastructure & Administration Lab
**Platform:** VMware Workstation | **Technology:** Windows Server

Built and practiced a Windows Server domain environment.

- Configured Active Directory Domain Services (AD DS).
- Practiced domain creation, domain joining, and domain controller configuration.
- Worked with DNS, DHCP, Group Policy (GPO), and Organizational Units (OU).
- Configured Remote Desktop Services (RDS/RDP).
- Documented practical tasks with screenshots and step-by-step notes.

🔗 **Explore my repositories:** [GitHub Profile](https://github.com/irfan-ahmmed-sayam)

### 3. CCNA – Networking Practical Learning
**Platform:** Cisco Packet Tracer

Practicing networking concepts through hands-on labs and configuration documentation.

- VLANs and Inter-VLAN Routing
- Static and Dynamic Routing
- OSPF
- ACL
- NAT/PAT
- GRE Tunneling
- Router and Switch Management

🔗 **Explore my repositories:** [GitHub Profile](https://github.com/irfan-ahmmed-sayam)

## 🎓 Education & Qualifications

- **B.Sc. in Computer Science & Engineering (CSE)** — Southeast University | 2024–Present
- **Diploma in Network Systems Administration (NSA)** — IsDB-BISEW IT Scholarship Programme, Batch GNSL-71 | Completed 2026
- **Diploma in Engineering (Electronics)** — Chandpur Polytechnic Institute | 2019–2023
- **Secondary School Certificate (SSC), Science** — Perpety High School | 2019

## 📚 Learning & Documentation

I use GitHub to maintain practical documentation, organize lab screenshots, and track my technical learning progress.

My documentation is organized into topic-based repositories and day-by-day folders so that each lab can be reviewed and revisited easily.

- **Windows Server:** Practical configuration notes and lab documentation.
- **CCNA:** Networking labs and configuration practice.
- **MikroTik:** RouterOS and network infrastructure practice.
- **Linux Server:** Linux fundamentals and administration practice.

## 📊 GitHub Overview

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=irfan-ahmmed-sayam&show_icons=true&hide_border=true&include_all_commits=true" alt="GitHub statistics">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=irfan-ahmmed-sayam&layout=compact&hide_border=true" alt="Most used languages">

<img src="https://streak-stats.demolab.com?user=irfan-ahmmed-sayam&hide_border=true" alt="GitHub streak">

</div>

## 🤝 Connect With Me

- **GitHub:** [github.com/irfan-ahmmed-sayam](https://github.com/irfan-ahmmed-sayam)
- **LinkedIn:** [linkedin.com/in/irfan-ahmmed-sayam](https://www.linkedin.com/in/irfan-ahmmed-sayam)
- **YouTube:** [youtube.com/@themeaningofn](https://www.youtube.com/@themeaningofn)
- **Facebook:** [facebook.com/irfan.ahmmed.sayam](https://www.facebook.com/irfan.ahmmed.sayam)
- **Email:** [irfan.sayam27@gmail.com](mailto:irfan.sayam27@gmail.com)

---

<div align="center">

**“Learning by doing, documenting every step, and improving every day.”**

</div>
'''

out = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=out, extra_args=["--standalone"])
print(out)
