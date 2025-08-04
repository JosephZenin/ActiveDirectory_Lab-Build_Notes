# 🐍 Operation: Snake Huntress  
_A Tactical Deployment of Windows-Based Lab Environments for Active Directory Mastery_

---

## 🎯 Objective

> Build, break, and understand the inner workings of a secure Windows domain environment, with a focus on Active Directory, DNS, user permissions, and network defense.

---

## 🧱 Environment Stack

| Component        | Details                        |
|------------------|-------------------------------|
| Virtualization   | VirtualBox / VMware            |
| Host OS          | Windows 10 / Kali Linux (optional) |
| Lab Machines     | Windows Server 2019, Windows 10 |
| Network Setup    | NAT + Host-Only Adapter         |
| Tools Used       | RSAT, PowerShell, Event Viewer  |

---

## 📚 Learning Sources

- *Practical Windows Forensics* (No Starch Press)
- *John Hammond AD Lab Guide*
- *TryHackMe – Windows Fundamentals*
- [Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/)

---

## 🛠️ Deployment Plan

### Phase 1: Setup  
- [x] Install Windows Server 2019  
- [x] Configure DNS, DHCP, and Static IP  
- [x] Promote to Domain Controller  
- [x] Join Windows 10 Client to Domain  

### Phase 2: Core AD Exploration  
- [x] Create Organizational Units (OUs)  
- [x] Add Users/Groups  
- [x] Apply Group Policy Objects (GPOs)  
- [x] Enable and Analyze Event Logging  

---

## 🧠 Lessons Learned (So Far)

- **Understanding of FSMO roles**
- **Importance of DNS in domain resolution**
- **How GPOs can restrict or empower users**
- **Security risks of misconfigured AD environments**

---

## 🖼️ Screenshots

_Add screenshots of Server Manager, DNS configs, ADUC (`dsa.msc`), GPO Editor, etc._

---

## 🚨 Next Phase: Detection & Defense

> Implement Sysmon, explore Windows Defender logs, and simulate basic attacks using tools like SharpHound and invoke-mimikatz (in safe, isolated test).

---

## 🔗 Resources

- [TryHackMe](https://tryhackme.com/)
- [HackTheBox Academy](https://academy.hackthebox.com/)
- [Sigma Rules](https://github.com/SigmaHQ/sigma)

---

## 🧪 Lab Status

> 🔄 Currently Active  
> 📅 Last Updated: `April 8, 2025`  
> 🧍 Operative: `Joseph Romero (callsign: Active Snake)`

---
