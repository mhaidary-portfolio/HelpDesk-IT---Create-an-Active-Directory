# 🧪 Active Directory Home Lab

Spin up a mini enterprise IT environment on a single machine to practice skills for HelpDesk and IT roles. This personal project documents reproducible steps, scripts, and screenshots so you can learn by doing and show concrete work to recruiters.

---

## 🔍 What this project is
A hands‑on lab that walks through installing and configuring:
- ✅ Active Directory Domain Services (AD DS)  
- ✅ DNS & DHCP integration  
- ✅ Group Policy Objects (GPOs) and common policy use cases  
- ✅ User/group provisioning (PowerShell automation) and role‑based OU design  
- ✅ Basic security: account lockout, LAPS, BitLocker key handling  
- ✅ Common operational tasks: backups, joining clients, troubleshooting logs

Designed to prepare you for HelpDesk / IT support interviews and entry‑level sysadmin roles.

---

## 📦 Included in the repo
- 🛠 Lab setup guide (VM configuration, network layout)  
- 🧾 PowerShell scripts: bulk user import, password reset, group sync  
- 🧭 GPO examples and walkthroughs (password policy, drive maps, Windows Update, and more)
- 🚨 Example incident response steps (disable compromised account, collect logs)  
- 📸 Screenshots and verification steps

---

## 📥 Software downloads
- 🔗 VirtualBox
- 🔗 Windows Server Evaluation ISO (2019/2022)  
- 🔗 Windows 10 / 11 Evaluation ISO (client VM)  
- 🧰 PowerShell (latest recommended)  
---

## 💾 System requirements
- Minimum: 4 GB RAM (8 GB recommended)  
- Basic familiarity with Windows and networking settings

---

## 🖥 Lab topology (quick)
- DC01 — Windows Server (Domain Controller, DNS, DHCP optional)  
- CLIENT01 — Windows 10/11 workstation (joined to the domain)  
- Networking: NAT + Host‑Only adapters (single‑host mini‑enterprise)

(Full VM settings in the Lab Setup Guide.)

---

## 🎯 Why this project
- Builds concrete, demonstrable skills recruiters want for HelpDesk/IT roles  
- Goes beyond click‑through tutorials with automation, security, and incident response examples  
- Reproducible on a single host for easy demos during interviews

---

## 🤝 Contributing & support
- ⭐ Star the repo if you find it useful  
- 🐞 Open an issue for questions or suggested additions  
- 🔀 Pull requests welcome for extra scripts, guides, or improvements

---

## 👨‍💻 About the author
Aspiring IT professional building practical labs to bridge theory and real‑world experience. Learning to be better.
