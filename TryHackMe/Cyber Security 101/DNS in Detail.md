# DNS in Detail – TryHackMe

**Room Type:** Beginner  
**Focus:** Domain Name System (DNS) architecture, resolution process, and security implications

---

## Overview
This room provides a detailed explanation of how the Domain Name System works behind the scenes. It focuses on DNS architecture, the resolution process, and why DNS is a critical dependency for almost all network communications.

## What I Learned
- The role of DNS in translating domain names into IP addresses  
- The step-by-step DNS resolution process from client to authoritative server  
- Differences between recursive resolvers and authoritative name servers  
- How DNS design choices impact performance, reliability, and security  
- Why DNS is commonly targeted in both reconnaissance and active attacks  

## Tools & Techniques Used
- **DNS Resolution Analysis** – Understanding how queries and responses flow through DNS components  
- **Record Inspection** – Interpreting common DNS record types used in real environments  
- **DNS Query Types** – Forward and reverse lookups for name and IP mapping  
- **Basic DNS Troubleshooting** – Identifying resolution failures and misconfigurations  

## Key Concepts Covered
- DNS hierarchy (root, TLD, authoritative servers)
- Recursive vs authoritative DNS
- Common DNS record types (A, AAAA, CNAME, MX, TXT, NS)
- Forward and reverse DNS lookups
- DNS as a reconnaissance and attack surface

## Takeaway
This lab builds a strong DNS foundation, which is essential for understanding network behavior, troubleshooting issues, and detecting DNS-based attacks in real-world environments.
