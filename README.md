# 👋 Hi, I'm Felipe Machado

🛡️ Cybersecurity student focused on **Offensive Security (Red Team)**  
🎯 Transitioning career into Information Security  
📚 CompTIA Security+ | Studying Computer Science  
🧠 Learning by breaking, understanding by rebuilding

---

## 🧠 About Me

I'm a cybersecurity enthusiast with a strong interest in **offensive security, infrastructure, and real-world attack simulations**.

I believe that true security comes from deeply understanding **how systems fail**, how attackers think, and how environments are misconfigured in practice — not just theory.

Currently focused on:
- Pentesting fundamentals
- Network security
- Linux & Windows internals
- Cloud & monitoring (Zabbix, AWS basics)
- Continuous hands-on learning

---

## 🔐 Areas of Interest

- 🔴 Red Team / Pentesting  
- 🌐 Network Security  
- 🖥️ Linux & Windows Internals  
- ☁️ Cloud Security (AWS fundamentals)  
- 📊 Monitoring & Visibility (Zabbix)  

---

## 🛠️ Technologies & Tools

### 🧑‍💻 Languages
![Python](https://img.shields.io/badge/-Python-000?style=flat&logo=python)
![Bash](https://img.shields.io/badge/-Bash-000?style=flat&logo=gnu-bash)

### 🔧 Tools & Platforms
![Linux](https://img.shields.io/badge/-Linux-000?style=flat&logo=linux)
![Kali Linux](https://img.shields.io/badge/-Kali_Linux-000?style=flat&logo=kalilinux)
![Zabbix](https://img.shields.io/badge/-Zabbix-000?style=flat&logo=zabbix)
![Git](https://img.shields.io/badge/-Git-000?style=flat&logo=git)
![AWS](https://img.shields.io/badge/-AWS-000?style=flat&logo=amazonaws)

---

## 📂 Featured Projects

### 🔍 Simple Port Scanner (Python)
A basic TCP port scanner built using Python sockets, focused on understanding how network services expose themselves.

```python
import socket

host = "www.google.com"
ports = [80, 443, 21, 22]

for port in ports:
    client = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
    response = client.connect_ex((host, port))

    if response == 0:
        print(f"[+] {port} is open")
