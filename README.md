# System Compromise Using Metasploit & Hydra (Penetration Testing Lab)

This project demonstrates a full penetration testing workflow using Hydra and Metasploit within a virtualized lab environment. The attack simulated system compromise of Linux and Windows XP virtual machines.

## 🎯 Objective
Gain hands-on experience in exploiting real-world vulnerabilities using ethical hacking tools and techniques, and demonstrate post-exploitation access.

---

## 🛠️ Tools & Setup

- **Hydra** – for brute-force password attacks
- **Metasploit Framework** – for exploiting SMB vulnerability
- **Armitage GUI** – for visualizing and launching exploits
- **Virtual Machines:**
  - Kali Linux (Attacker)
  - Metasploitable2 (Linux target)
  - Windows XP SP3 (vulnerable target)

---

## 🔐 Attack Steps

1. **Password Brute Force with Hydra**:
   - Targeted SSH login on the Linux VM using Hydra to discover valid credentials.

2. **Exploitation Using Metasploit**:
   - Used `exploit/windows/smb/ms08_067_netapi` on the vulnerable Windows XP SP3 VM.
   - Configured payload `windows/meterpreter/reverse_tcp`.

3. **Post-Exploitation**:
   - Gained a Meterpreter shell
   - Verified remote system access and executed basic commands

---

## 📸 Screenshot

![Armitage Exploit](https://raw.githubusercontent.com/Aarushh19/system-compromise-penetration-lab/main/BothVMscompromised.png)

---

## ✅ Learning Outcomes

- Gained practical understanding of exploit development and post-exploitation
- Learned how to configure payloads and sessions in Metasploit
- Understood vulnerability implications on unpatched systems (MS08-067)

---

## ⚠️ Disclaimer

This lab was conducted in a safe, isolated academic environment for ethical and educational purposes only.

---

© Aarush Gupta | MS Cybersecurity & Privacy | University of Central Florida
