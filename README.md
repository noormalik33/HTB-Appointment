# HTB-Appointment: SQLi Gateway & OSINT Intelligence 🚀

> A specialized penetration testing and threat intelligence lab showcasing SQL Injection web exploitation alongside advanced Open-Source Intelligence (OSINT) reconnaissance matrices.

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-HackTheBox-blue?style=for-the-badge)
![Category](https://img.shields.io/badge/Category-Web%20Exploitation%20%2F%20OSINT-red?style=for-the-badge)

---

## 📌 Academic Evaluation Details

This laboratory project was executed as part of the security curriculum guidelines under structural academic evaluation:

* [cite_start]**Institution:** Air University, Islamabad [cite: 443]
* [cite_start]**Student Name:** Noor Malik [cite: 438]
* [cite_start]**Roll Number:** 230964 [cite: 439]
* [cite_start]**Section:** BSIT-VI-B [cite: 440]
* [cite_start]**Submitted To:** Sir Ayaz [cite: 442]

---

## 📱 Project Overview

[cite_start]**HTB-Appointment** is an attack-and-reconnaissance simulation that targets data validation flaws within corporate authentication portals[cite: 479]. [cite_start]The lab starts by attacking a vulnerable web interface via SQL injection (SQLi)  [cite_start]and scales into a multi-tier passive intelligence harvesting operation simulating professional target profiling.

This lab was built to practice and showcase:
- [cite_start]Automated web infrastructure discovery via active VPN tunnels [cite: 459, 485]
- [cite_start]Authentication bypass constraints using customized **SQL Injection** payloads 
- [cite_start]External digital footprint auditing with **Netcraft** and **Censys** [cite: 506, 732, 740]
- [cite_start]Corporate communication harvesting using **theHarvester** [cite: 630, 634]
- [cite_start]Dark Web threat profile intelligence via isolated proxy nodes (**Tor Browser**) 

---

## ✨ Key Features

### 🔐 Web Application Boundary Exploitation (SQLi)
- [cite_start]**Target Isolation:** Maintained a stable tunnel constraint over target node `10.129.21.69` using localized OpenVPN layers[cite: 453, 459].
- [cite_start]**Vulnerability Leveraged:** Poor parameter validation on input fields within the target's HTTP POST login request wrapper[cite: 479].
- [cite_start]**Authentication Bypass:** Crafted a structured inline SQL injection logic payload (`' OR 1=1--`) inside the username vector to trick the database engine interpreter, bypassing password checks entirely and successfully capturing the target flag string[cite: 494, 502, 503].

### 🌐 Digital Brand Asset Profiling (Netcraft & Censys)
- [cite_start]**Passive Infrastructure Mining:** Audited `microsoft.com` domains using **Netcraft Data Analytics** to catalog running technologies, active site tracking scripts, HTML schemas, and SPF record architectures[cite: 535, 543, 552, 564].
- [cite_start]**Global Asset Mapping:** Utilized **Censys Scanning Frameworks** to track public-facing certificates, server headers, and underlying Operating Systems for specific enterprise properties like `eccouncil.org`[cite: 732, 740, 752, 771].

### 📧 Structural Directory Harvesting (theHarvester)
- [cite_start]Automated programmatic OSINT analysis against the target domain scope (`microsoft.com`) using **theHarvester engine** mapped directly through search aggregators like Bing[cite: 630, 634].
- [cite_start]Focused on intercepting valid employee identity keys, active host registries, and leaked mail drops within public indexes[cite: 634].

### 👥 People Footprint Traversal (PeekYou)
- [cite_start]Profiled targeted personnel directories (e.g., Satya Nadella) via deep-web indices on **PeekYou** to isolate personal background info, public historical records, and associated digital aliases across social boundaries[cite: 569, 584, 585, 593].

### 🧅 Dark Web Risk & Scam Assessment
- [cite_start]Routed traffic through encrypted proxy enclaves (**Tor Project Engine**) to safely inspect non-indexed `.onion` digital marketplaces[cite: 645, 651, 731].
- [cite_start]Formulated clear risk differentiation maps comparing standard surface indexes against hidden darknets, highlighting high-probability fraud traps like fake "Hacker-for-Hire" operations[cite: 688, 695, 729].

---

## 🛠️ Tech Stack

- [cite_start]**Operating Systems:** Kali Linux Platform [cite: 461][cite_start], Parrot Security OS [cite: 177]
- **Target Context:** Apache Web Infrastructure, Relational Database Backends
- [cite_start]**OSINT Framework Engines:** Netcraft Analytics [cite: 510][cite_start], Censys Data Registry [cite: 740][cite_start], theHarvester CLI [cite: 635][cite_start], PeekYou Database [cite: 571]
- [cite_start]**Anonymity Networks:** Tor Proxy Routing Architecture [cite: 651]

---

## 🚀 How to Run & Verify

1. **Clone the repository**
   ```bash
   git clone [https://github.com/noormalik33/HTB-Appointment.git](https://github.com/noormalik33/HTB-Appointment.git)

  

2. **Establish OpenVPN Tunnel Connection**
```bash
[cite_start]sudo openvpn starting_points_us-starting-point-1-dhcp.ovpn [cite: 462]

```


3. **Deploy Authentication Attack Strings**
Navigate to the target portal endpoint (`http://10.129.21.69`) and input the following parameter string inside the login fields:


* **Username Box:** `admin' OR 1=1--`
* **Password Box:** `[Any String / Blank]`


4. **Run CLI-Based OSINT Scripts**
```bash
[cite_start]theHarvester -d microsoft.com -l 200 -b bing [cite: 634]

```



---

## 🎯 Learning Outcomes

* Manipulating unescaped database syntax paths inside standard production login forms.


* Aggregating structured information tables across passive OSINT engines without tripping target detection logs.


* Inspecting live server banners, SSL certificates, and software versions globally.


* Managing anonymous browsing setups safely inside defensive assessment environments.



## 📄 License

This project is licensed under the **MIT License**.
See the `LICENSE` file for more details.

---

## Contributing 🤝

Contributions are welcome! Please fork the repository, make changes, and submit a pull request. Report bugs or suggest features via GitHub Issues. 🌟

## Contact 📬
For questions, feedback, or collaboration, reach out to:

---

## 👨‍💻 Developer

**Noor Malik**
IT Student | Full-Stack Software Developer | Android App Developer 
  
📍 Islamabad, Pakistan  
📧 Email: noormalik56500@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/noormalik56500/)

Social 📱

📧 Email:coreittech1@gmail.com  
📹 YouTube1: https://www.youtube.com/@CoreITTech1  
📹 YouTube2: https://www.youtube.com/@CoreITTech  
📸 Instagram: https://www.instagram.com/coreit.tech  
📘 Facebook: https://www.facebook.com/share/1AmgLDUnc9/

---


💡 If you like this project, don’t forget to star ⭐ it on GitHub!

Happy hunting! 🚀 Let’s keep securing systems together! 💪

---

⭐ *If you found this project helpful, feel free to star the repository!*
🧠 *Created for educational and portfolio demonstration purposes.*

```

   
