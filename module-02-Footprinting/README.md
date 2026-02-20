# 🕵️ Module 02 – Footprinting Report

## 📖 Overview
This repository contains the practical report for **Module 02 – Footprinting** from CEHv13.

Footprinting is the first phase of Ethical Hacking where information about a target system, organization, or network is collected using passive and active reconnaissance techniques.

---

## 🎯 Objectives

- Understand footprinting concepts
- Perform passive and active reconnaissance
- Use Google Dorking for information gathering
- Conduct WHOIS and DNS lookup
- Perform Network and Email footprinting
- Use tools like Recon-ng and Sherlock

---

# 1️⃣ Introduction to Footprinting

Footprinting is the process of collecting information about a target before performing a security assessment.

### Types of Footprinting:
- Passive Footprinting
- Active Footprinting

---

# 2️⃣ Google Dorking

Google Dorking uses advanced search operators to find publicly available information.

### Common Operators:
site:example.com
filetype:pdf site:example.com
intitle:"login"
inurl:admin

---

# 3️⃣ Internet Research Services

## 🔹 Netcraft
Used to identify:
- Hosting provider
- Server details
- Technology stack

## 🔹 DNS Dumpster
Used for:
- Subdomain discovery
- DNS mapping

---

# 4️⃣ Social Media Footprinting

## 🔹 Sherlock
Used for username enumeration.

Example:python3 sherlock username

---

# 5️⃣ WHOIS Footprinting

WHOIS provides:
- Domain owner details
- Registrar information
- Registration & expiry dates
- Name servers

---

# 6️⃣ DNS Footprinting

## NSLookup (CLI)
nslookup example.com
nslookup -type=mx example.com
Used to retrieve DNS records like:
- A records
- MX records
- NS records

---

# 7️⃣ Network Footprinting

## Windows
tracert example.com

## Linux
traceroute example.com
Used to trace routing path and identify hops.

---

# 8️⃣ Email Footprinting

## 🔹 GSA Email Spider
Extracts publicly available email addresses.

## 🔹 MX Toolbox
Used for:
- MX record lookup
- Mail server analysis

---

# 9️⃣ Recon-ng

Recon-ng is an OSINT framework used for automated reconnaissance.
Basic workflow:
marketplace search
modules load
run


---

# ⚠️ Disclaimer

This project is created strictly for educational purposes only.

All demonstrations were performed in a controlled lab environment. Unauthorized reconnaissance on real systems without permission is illegal.
