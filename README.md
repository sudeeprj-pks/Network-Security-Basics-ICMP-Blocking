# Cyber Security Intern Assignment

## Task 1: Introduction to Network Security Basics

---

## 1. Objective

The objective of this task is to understand the **fundamentals of network security** by identifying common network threats and implementing basic security measures in a small network environment. This task provides a foundation for securing systems against common cyber attacks and understanding how defensive controls protect networks.

---

## 2. Network Security Concepts

### 2.1 Common Network Threats

**1. Viruses**
Viruses are malicious programs that attach themselves to legitimate files or applications. When the infected file is executed, the virus spreads and can damage files, corrupt data, or disrupt system operations.

**2. Worms**
Worms are self-replicating malware that spread automatically across networks without user interaction. They consume bandwidth and system resources and can cause large-scale network outages.

**3. Trojans**
Trojans disguise themselves as legitimate software but contain malicious code. Once installed, they may create backdoors, steal sensitive data, or give attackers remote access to the system.

**4. Phishing Attacks**
Phishing is a social engineering attack where attackers trick users into revealing sensitive information such as passwords or banking details by impersonating trusted entities through emails or fake websites.

---

### 2.2 Basic Security Concepts

**Firewalls**
A firewall monitors and controls incoming and outgoing network traffic based on predefined security rules. It acts as a barrier between trusted internal networks and untrusted external networks.

**Encryption**
Encryption converts data into unreadable formats to protect confidentiality. Common examples include HTTPS for web traffic and WPA2/WPA3 for wireless networks.

**Secure Network Configuration**
This includes changing default passwords, disabling unnecessary services, keeping systems updated, and using strong authentication methods to reduce attack surfaces.

---

## 3. Implementation of Basic Security Measures

### 3.1 Network Environment Setup

A simple network environment was created using:

* One primary system (host machine)
* One secondary system or virtual machine
* A router providing internet connectivity

---

### 3.2 Firewall Configuration

**Tool Used:** Windows Defender Firewall

Actions performed:

* Enabled firewall for all profiles (Domain, Private, Public)
* Verified that unsolicited inbound traffic is blocked by default
* Created basic inbound and outbound rules to restrict unauthorized access

**Reason:**
Firewalls prevent unauthorized network access and reduce the risk of attacks such as port scanning and exploitation.

---

### 3.3 Secure Network Configuration

Security configurations implemented:

* Changed default router and system passwords
* Enabled strong password policies
* Enabled network encryption using **WPA2/WPA3** on the wireless network

**Reason:**
Strong authentication and encryption protect against unauthorized access and eavesdropping.

---

## 4. Network Traffic Monitoring Using Wireshark

### 4.1 Tool Used

* **Wireshark** (Network Protocol Analyzer)

---

### 4.2 Traffic Captured and Analyzed

**1. HTTP Traffic**
Observed unencrypted web traffic showing request and response details. This highlights the risk of transmitting sensitive data without HTTPS.

**2. DNS Traffic**
Captured DNS queries and responses used for domain name resolution. DNS traffic is essential for network communication but can also be abused by attackers.

**3. ARP Traffic**
ARP packets were observed resolving IP addresses to MAC addresses within the local network.

---

### 4.3 Identifying Suspicious Traffic

Indicators of suspicious activity include:

* Repeated failed connection attempts
* Unusual DNS requests
* Unexpected traffic to unknown IP addresses

Wireshark helps identify these patterns by analyzing packet details and communication behavior.

---

## 5. Documentation of Findings

### 5.1 Summary of Network Threats

* Malware such as viruses, worms, and trojans can disrupt systems and steal data
* Phishing attacks target human weaknesses rather than technical vulnerabilities

### 5.2 Security Measures Implemented

* Firewall enabled and configured
* Secure passwords and encryption applied
* Network traffic monitored using Wireshark

### 5.3 Traffic Capture Evidence

* HTTP, DNS, and ARP traffic observed using Wireshark
* Traffic analysis helped understand normal vs abnormal behavior

### 5.4 Effectiveness of Security Measures

These basic security controls significantly reduce risk by:

* Blocking unauthorized access
* Protecting data confidentiality
* Detecting abnormal network activity early

---

## 6. Reflection on Security Best Practices

### 6.1 Additional Security Measures for Larger Networks

In larger networks, additional protections could include:

* Intrusion Detection and Prevention Systems (IDS/IPS)
* Network segmentation using VLANs
* Centralized logging and SIEM solutions
* Regular vulnerability scanning and patch management

---

### 6.2 Educating Users on Network Security

Educating users is essential for strong security. Users should be taught to:

* Recognize phishing emails and suspicious links
* Use strong, unique passwords
* Keep systems updated
* Understand the importance of secure networks in everyday activities such as online banking and communication

---

## 7. Conclusion

This task provided a strong foundation in **network security basics**. By understanding common threats, implementing firewalls and secure configurations, and analyzing network traffic, it is possible to significantly improve the security posture of a small network. These concepts form the basis for more advanced cybersecurity practices.

---

**Intern Role:** Cyber Security Intern
**Task:** Introduction to Network Security Basics
**Tools Used:** Windows Defender Firewall, Wireshark
