# 🔐 Medusa Phisher
## QR Code Security & Phishing Awareness

<p align="left">
  <img src="https://img.shields.io/badge/Purpose-Education-blue" />
  <img src="https://img.shields.io/badge/Security-Awareness-red" />
  <img src="https://img.shields.io/badge/Ethical%20Hacking-Only-green" />
</p>

---

## ⚠️ Disclaimer

🚨 This project is intended strictly for **educational purposes** and **cybersecurity awareness**.

The goal of this material is to:
- Explain modern phishing techniques  
- Demonstrate how attackers exploit user behavior  
- Help individuals and organizations recognize and prevent attacks  


❗ **Do NOT use this knowledge for malicious purposes.**

---

## 📱 Chapter 1: QR Codes and the Concept of "Quishing"

QR codes are convenient and widely used, but they can also present security risks.

The main concern is that:
- Users cannot see the destination link before scanning  
- Malicious QR codes look identical to legitimate ones  
- They are commonly found in public spaces  
- People tend to trust them automatically  

This type of attack is known as **quishing (QR phishing)** — a form of social engineering that relies on trust, curiosity, and human behavior rather than technical vulnerabilities.

Unlike traditional phishing links, QR codes hide the URL until they are scanned, making deception easier.

---

## 💻 Chapter 2: Using Kali Linux in a Virtual Environment

**Kali Linux** is a specialized Linux distribution used for cybersecurity education and ethical security testing.

It is strongly recommended to use Kali inside a **virtual machine** (such as VirtualBox or VMware). This keeps the system isolated from the main operating system, improving safety and control.

### System Update Commands

The first step is running:

```bash
sudo apt update
```

This command refreshes the list of available software packages from the official repositories. It checks for the latest versions but does not install them.

Next, run:

```bash
sudo apt upgrade
```

This command installs the newest available versions of the installed packages. It helps improve system stability, performance, and security by applying updates.

Keeping the system updated is an essential practice in cybersecurity, as it reduces vulnerabilities and ensures that tools function correctly.

Using Kali Linux responsibly in a virtual environment allows students to learn about security concepts in a controlled and ethical way.

```bash
git clone <repository_url>
```

Downloads a repository from a remote source to the local system.  

```bash
chmod +x <file_name>
```

Gives execution permission to a file (allows it to run as a program or script).

```bash
ssh-keygen -t rsa -b 4096 -C "user@example.com"
```

Generates a secure RSA key pair (public and private key).  

---

## 🎯 Chapter 3: QR-Based Phishing Scenario (Defensive Overview)

In an educational demonstration, a QR code may redirect users to a deceptive website.

### How the Attack Works (Conceptually)

1. A user scans a QR code  
2. The code redirects to a malicious website  
3. The website imitates a trusted platform  
4. The user enters login credentials  
5. The attacker attempts to capture the information  

This technique is a form of **social engineering**, targeting human trust rather than system weaknesses.

---

## 🧠 Psychology Behind Social Engineering

Attackers often use psychological triggers such as:

- ⏰ **Urgency** – “Your account will be locked”  
- 👀 **Curiosity** – “Scan to see exclusive content”  
- 🏛️ **Authority** – Fake logos and branding  
- 🤝 **Trust** – Public placement of QR codes  
- ⚡ **Convenience** – Quick access without typing URLs  

Quishing combines physical elements (QR codes) with digital deception, making it more difficult to detect.

---

## 🛡️ How to Protect Yourself

### Before Scanning
- Only scan QR codes from trusted sources  
- Avoid codes placed over stickers or modified posters  
- Be cautious in public environments  

### After Scanning
- Carefully check the URL  
- Look for spelling errors in the domain name  
- Ensure the website is legitimate  
- Avoid entering sensitive information on unknown sites  

### Account Security
- Enable **Multi-Factor Authentication (MFA)**  
- Use strong and unique passwords  
- Avoid password reuse across platforms  
- Keep devices and applications updated  

---

## 🏢 How Organizations Defend Against These Attacks

Companies use several security measures, including:

- URL filtering and web reputation systems  
- Email security gateways  
- Endpoint protection software  
- Suspicious login monitoring  
- Security awareness training  
- Zero-trust security models  

These strategies reduce risk and improve overall security posture.

---

## 📌 Key Takeaway

QR-based phishing demonstrates how modern cyberattacks combine technology and psychology.

The most effective defense includes:

- Education  
- Awareness  
- Verification  
- Strong authentication practices  

Security is not only about tools — it is about informed decision-making.

🔐 **Think before you scan. Awareness is your strongest defense.**

