# cisco-project
# Network Design & Configuration Project 🌐

## 📌 Description
This project demonstrates the design and implementation of a secure and scalable network using multiple networking concepts.

---

## 🔧 Technologies & Concepts
- VLAN (Virtual LAN)
- STP (Spanning Tree Protocol)
- NAT (Network Address Translation)
- DHCP (Dynamic Host Configuration Protocol)
- DNS (Domain Name System)
- Port Security
- ACLs (Access Control Lists)
- Broadcast & Collision Domains

---

## 🧠 Project Features
- Segmented network using VLANs
- Loop prevention using STP
- IP address management using DHCP
- Secure access control using ACLs and Port Security
- Internet access simulation using NAT
- Name resolution using DNS

---

## 🖼️ Network Topology
(Add your topology image here)

---

## 🔐 Security Implementation
- Port Security applied to switches
- ACLs used to restrict unauthorized access

---

## 🚀 Key Learnings
- Practical implementation of networking concepts
- Network security fundamentals
- Traffic control and segmentation
- Real-world network design skills

---



## ⚠️ Troubleshooting & Challenges

### 🔍 Issue: NAT translations not appearing

While testing NAT, the command:
`show ip nat translations.`
did not show any entries, even though connectivity was successful.

### 🧠 Cause
ICMP traffic (ping) does not always create visible NAT entries on some devices.

### 🛠️ Solution
Used TCP traffic instead:
`telnet 200.0.0.2 80`

After that, NAT entries appeared correctly.

### 💡 Lesson Learned
Always test NAT using appropriate traffic types, not only ICMP.


## 👩‍💻 Author
Nour Ahmed
