# DNS Manipulation – TryHackMe

**Room Type:** Intermediate  
**Focus:** DNS resolution mechanics, manipulation techniques, and defensive considerations

---

## Overview
This room dives deeper into how the Domain Name System (DNS) operates and how attackers can abuse it to redirect traffic, intercept communications, or disrupt services. It emphasizes DNS as a trust-based system and explains why weaknesses in DNS handling can have serious security implications.

## What I Learned
- The full DNS resolution workflow, from client query to authoritative response  
- Where DNS trust assumptions exist and how attackers exploit them  
- How DNS manipulation enables attacks such as phishing, traffic redirection, and MITM  
- Why DNS-based attacks are difficult for end users to notice  
- How defenders can reduce risk through monitoring and validation mechanisms  

## Tools & Techniques Used
- **DNS Query Inspection** – Analyzing DNS requests and responses to identify anomalies  
- **DNS Spoofing Techniques** – Forging DNS replies to redirect victims to malicious endpoints  
- **Cache Poisoning** – Injecting false records into a resolver’s cache to persist redirection  
- **Defensive DNS Controls** – Applying validation, logging, and monitoring to detect abuse  

## Key Concepts Covered
- DNS resolution chain (client, resolver, authoritative server)
- Trust relationships in DNS
- DNS spoofing and redirection
- DNS cache poisoning
- Security risks of unvalidated DNS responses

## Takeaway
This lab demonstrates how manipulating DNS can silently compromise users and services, making DNS security knowledge essential for both attackers and defenders in real-world networks.
