# cybersecurity-notes
Hands-on cybersecurity labs completed through TryHackMe and Nucamp bootcamp training
# Cybersecurity Labs: TryHackMe Walkthroughs

This repository contains selected notes and summaries from hands-on cybersecurity training using the TryHackMe platform. These labs were completed through Nucamp’s Cybersecurity Bootcamp and serve as preparation for the CompTIA Security+ (SY0-701) exam, scheduled for September 2025.

---

## 🔐 Lab 1: Mr. Robot CTF
**Skills Covered:** Enumeration, brute force, privilege escalation

- Identified open ports using `nmap` (22, 80, 443)
- Discovered Wordpress CMS and used `wpscan` to enumerate users and plugins
- Cracked hashed passwords using `john` and gained shell access
- Performed privilege escalation via SUID abuse with `nmap` interactive mode
- Recovered all three flags: `key-1`, `key-2`, and `key-3`

---

## 🧰 Lab 2: Kenobi CTF
**Skills Covered:** SMB enumeration, ProFTPd exploit, local privilege escalation

- Scanned ports using `nmap` and identified Samba and ProFTPd services
- Used `enum4linux` and `smbclient` to enumerate shares and extract local credentials
- Identified ProFTPd vulnerability and used `Metasploit` to gain a foothold
- Performed LPE via SUID binary and retrieved both `user.txt` and `root.txt`

---

## 🛠️ Tools Used
- Kali Linux  
- Nmap, Burp Suite, Gobuster  
- Enum4linux, Hydra  
- John the Ripper  
- Metasploit Framework  

------

## 🏛️ Governance & Risk Case Study

This section includes written work developed during my Network Security coursework focused on Governance, Risk, and Compliance (GRC). These case studies apply frameworks such as NIST 800-30 and HIPAA Security Rule standards to practical enterprise risk scenarios.

📄 **[HHS SRA Report](https://github.com/jimdelciello/cybersecurity-notes/blob/main/HHS%20SRA%20Report%204%205%2025.pdf)**  
A simulated Security Risk Assessment for a healthcare organization using HIPAA and NIST 800-30 methodologies. Covered administrative, technical, and physical safeguards; identified threats; and proposed actionable mitigation strategies.

📄 **[TechNova Memorandum](https://github.com/jimdelciello/cybersecurity-notes/blob/main/TechNova%20Memorandum%204%205%2025.pdf)**  
An internal risk advisory memo addressing governance gaps, residual risks, and information assurance objectives aligned with NIST-based risk modeling.

> *Instructor Feedback:*  
> *"Exceptional work. This will serve as a benchmark for future students."*


## 🧠 Certification Path
- **CompTIA Security+ (SY0-701)** – Exam scheduled for September 2025
- Additional training via TryHackMe, Nucamp labs, and real-world CTF challenges

---

### 🔗 Connect with Me
I’m exploring cybersecurity roles focused on compliance, GRC, and security operations.  
[LinkedIn Profile](https://www.linkedin.com/in/jim-del-ciello-245b8a32/)
