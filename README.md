# 🌐 Mobile Network & Port Security Simulation

This lab demonstrates the setup of a secure wireless and mobile infrastructure using **Cisco Packet Tracer**.

## 🚀 Technical Highlights
* **Wireless Setup:** Configured a WRT300N Router with **DHCP** (50 IP limit) and **WEP Encryption**[cite: 4].
* **Layer 2 Security:** Implemented **MAC Address Filtering** on a 2960 Switch.
* **Sticky MAC:** Used `switchport port-security mac-address sticky` to lock port fa0/2 to a specific device[cite: 4].
* **Mobile Integration:** Connected a Cell Tower to a Central Services office via Coaxial cabling[cite: 4].

## 🧪 Testing & Results
* **Connectivity:** Verified via ICMP pings from a Smartphone to a PC and Laptop.
* **Troubleshooting:** Analyzed initial packet loss (1/4) and confirmed 100% success (4/4) upon network convergence[cite: 4].

---
📂 *Full technical report and simulation files are included in this repository.*
