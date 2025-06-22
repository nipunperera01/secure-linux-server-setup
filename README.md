# 🔐 Secure Linux Web Server Setup (Ubuntu + Apache + UFW + Fail2ban)

This project demonstrates how to set up and secure a basic web server in a virtualized lab environment using Ubuntu Server, Apache2, UFW, and Fail2ban.

---

## 🧰 Technologies Used

- Ubuntu Server 22.04 LTS (VMware)
- Apache2 Web Server
- UFW Firewall
- Fail2ban (SSH Brute-force protection)
- VMware Workstation Player

---

## ⚙️ Configuration Steps

- ✅ Installed and configured Apache2 on Ubuntu
- ✅ Allowed only necessary ports using UFW (SSH, HTTP)
- ✅ Installed and configured Fail2ban to monitor and ban SSH brute-force attacks
- ✅ Tested local Apache site access via IP
- ✅ Captured logs and system data for documentation

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `jail.local` | Fail2ban configuration for SSH |
| `system-info.txt` | OS and system information |
| `screenshots/` | Apache browser view, firewall and Fail2ban terminal outputs |

---

## 📷 Screenshots

_(Located in `screenshots/` folder)_
- Apache default page in browser
- UFW firewall status
- Fail2ban SSH protection status
- Active services from terminal

---

## 💡 Skills Gained

- Linux System Administration  
- Apache Web Hosting  
- Basic Firewall Management (UFW)  
- SSH Hardening with Fail2ban  
- Working with system services and logs  
- Virtualization Lab Setup (VMware)

---

## 📌 Author

**Nipun Perera**  
Networking Undergraduate – NSBM Green University, Sri Lanka 🇱🇰

---

