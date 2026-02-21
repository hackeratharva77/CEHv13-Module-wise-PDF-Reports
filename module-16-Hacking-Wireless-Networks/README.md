# 📡 Hacking Wireless Networks

------------------------------------------------------------------------

## 📌 Introduction

Hacking wireless networks means attempting to gain unauthorized access to a Wi-Fi network or intercept the data being transmitted over it.
In simple words:
It is when someone tries to break into a Wi-Fi network without permission.
Wireless networks are vulnerable because signals travel through the air.
If not properly secured, attackers can intercept traffic, crack weak
passwords, or create fake access points.

------------------------------------------------------------------------

## 🎯 Objectives

-   Understand common Wi-Fi security threats.
-   Learn how attackers target weak wireless networks (theoretical
    knowledge).
-   Identify misconfigurations in wireless setups.
-   Understand security testing tools used by ethical hackers.
-   Apply best practices to secure wireless networks.

------------------------------------------------------------------------

## 📂 Common Wireless Network Attacks (Conceptual)

### 1. Brute Force / Password Cracking

Targeting weak WPA/WPA2 passwords. Prevented by strong passwords & WPA3.

### 2. Evil Twin Attack

Fake Wi-Fi network created to mimic a legitimate one. Users connect
unknowingly and attackers capture traffic.

### 3. Deauthentication Attack

Forcing devices to disconnect from Wi-Fi. Often used in testing Wi-Fi
security robustness.

### 4. Packet Sniffing

Capturing unencrypted wireless traffic. Dangerous on open Wi-Fi
networks.

### 5. WPS Exploitation

Exploiting weak Wi-Fi Protected Setup PIN configurations.

------------------------------------------------------------------------

## 🧰 Common Tools (Used by Ethical Hackers & Security Professionals)

-   Aircrack-ng -- Wireless network security auditing suite.
-   Wireshark -- Packet capture and traffic analysis tool.
-   Kismet -- Wireless network detection and monitoring tool.
-   Reaver -- Used to test WPS vulnerabilities (authorized testing
    only).
-   Kali Linux -- Security testing operating system.

⚠️ These tools should only be used in lab environments or with written
permission.

------------------------------------------------------------------------

## 🛡️ Defensive Countermeasures

-   Use WPA3 encryption (avoid WEP/WPA).
-   Disable WPS if not required.
-   Set a strong, complex Wi-Fi password (12--16+ characters).
-   Change default router credentials.
-   Enable MAC filtering (additional layer, not primary security).
-   Keep router firmware updated.
-   Use VPN on public Wi-Fi networks.

------------------------------------------------------------------------

## 🔐 Secure Configuration Best Practices

-   Change default router admin password immediately.
-   Use AES encryption only.
-   Separate guest and internal networks.
-   Enable firewall on router.
-   Monitor connected devices regularly.

------------------------------------------------------------------------

## ⚠️ Disclaimer

This material is provided for educational and defensive cybersecurity
purposes only. Testing wireless networks without explicit authorization
is illegal and punishable under cybercrime laws.
