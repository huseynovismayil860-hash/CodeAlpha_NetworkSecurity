# SOHO (Small Office/Home Office) Network Security Configuration Guide

This project was developed for the Cyber Security Internship at **CodeAlpha**. It serves as a practical, step-by-step configuration guide to securing a Small Office or Home Office (SOHO) network against common cyber threats.

## 🛡️ Core Security Implementations

### 1. Router & Access Point Security
* **Change Default Credentials:** Immediate replacement of factory-default admin passwords with strong, unique passphrases to prevent unauthorized access to router settings.
* **Firmware Updates:** Enabling automatic firmware updates to patch newly discovered security vulnerabilities in the router's operating system.

### 2. Wireless Network (Wi-Fi) Hardening
* **WPA3 Encryption:** Implementing WPA3 (or WPA2-AES as a minimum) encryption protocol to secure wireless traffic from eavesdropping.
* **SSID Management:** Disabling SSID broadcasting or renaming the Wi-Fi network to a neutral name that does not disclose the router model or owner identity.
* **Guest Network Isolation:** Setting up a separate virtual local area network (VLAN) or Guest Network for smart devices (IoT) and visitors, ensuring they cannot access critical network resources.

### 3. Network Defense & Monitoring
* **Firewall Activation:** Enabling the router’s built-in Stateful Packet Inspection (SPI) firewall to block malicious inbound traffic.
* **MAC Address Filtering:** Restricting network access only to whitelisted, pre-approved device MAC addresses.
* **Disabling Vulnerable Services:** Turning off **WPS (Wi-Fi Protected Setup)** and **UPnP (Universal Plug and Play)**, which are frequently exploited by attackers to bypass authentication.

---

## 📂 Project Structure
* `README.md` - The complete architectural guide for SOHO network hardening.

## 📝 Internship Details
* **Company:** CodeAlpha
* **Domain:** Cyber Security
* **Task:** Task 3 - Network Security Configuration
