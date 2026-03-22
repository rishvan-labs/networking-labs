# 🔐 Network Security using ACL (Cisco)

## 📌 Overview
This project demonstrates how Access Control Lists (ACLs) are used to filter network traffic and improve security.

---

## 🎯 Objectives
- Understand Standard and Extended ACLs
- Control traffic between networks
- Implement security policies
- Test and verify ACL behavior

---

## 🛠️ Tools Used
- Cisco Packet Tracer

---

## ⚙️ Configuration

### Standard ACL Example
```
access-list 10 deny 192.168.1.10
access-list 10 permit any
interface g0/0
ip access-group 10 in
```

### Extended ACL Example
```
access-list 100 deny tcp 192.168.1.0 0.0.0.255 any eq 80
access-list 100 permit ip any any
interface g0/1
ip access-group 100 out
```

---

## 📸 Topology
(Add your network diagram here)

---

## 🔍 Testing
- Ping test
- Access restriction verification

---

## 🧠 Learning Outcomes
- Traffic filtering using ACL
- Network security basics
- Cisco configuration skills

---

## ⚠️ Disclaimer
This project is for educational purposes only.
