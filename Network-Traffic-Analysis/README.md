# Network Traffic Analysis: DNS and ICMP Investigation

## Project Overview

This project focuses on investigating a network connectivity issue affecting a client's website, `www.yummyrecipesforme.com`.

As part of this cybersecurity investigation, I used **tcpdump**, a command-line network packet analyzer, to examine DNS and ICMP traffic and identify the possible cause of the website accessibility problem.

## 1. Problem Description

Customers reported that they were unable to access the client's website. When attempting to load the website, users received an error indicating that UDP port 53 was unreachable.

Using tcpdump to analyze the network traffic, I identified ICMP error messages indicating:

**"UDP Port 53 Unreachable"**

Port 53 is commonly used by DNS services to translate domain names into IP addresses. The ICMP error indicated that DNS requests were not reaching an available DNS service successfully.

As a result, users were unable to resolve the website's domain name and access the website.

## 2. Investigation and Analysis

I initiated a network traffic investigation using tcpdump to examine the DNS and ICMP packets captured during the incident.

The analysis identified the following findings:

- Customers experienced difficulties accessing `www.yummyrecipesforme.com`.
- The incident was observed at approximately 1:24 PM.
- DNS requests were sent using UDP.
- ICMP error messages reported that UDP port 53 was unreachable.
- DNS resolution was unsuccessful, preventing users from accessing the website through its domain name.

## 3. Key Findings

| Area | Finding |
|---|---|
| Website | www.yummyrecipesforme.com |
| Network protocol | DNS and ICMP |
| Transport protocol | UDP |
| Affected port | 53 |
| Error message | UDP Port 53 Unreachable |
| Analysis tool | tcpdump |
| Approximate incident time | 1:24 PM |

## 4. Possible Causes of the Incident

Based on the packet analysis, several possible causes were identified:

1. **DNS Server Unavailability:** The DNS service may have been down or unavailable.
2. **Firewall Configuration:** Firewall rules may have been blocking DNS traffic on UDP port 53.
3. **Network Misconfiguration:** Incorrect network settings may have prevented DNS requests from reaching the DNS server.
4. **Potential Malicious Activity:** A denial-of-service attack could potentially disrupt DNS availability, although the packet evidence alone does not confirm malicious activity.

## 5. Recommended Actions

Based on the investigation, I recommend the following actions:

- Verify that the DNS server is operational and responding to requests.
- Review firewall rules to ensure legitimate DNS traffic is permitted.
- Check network configurations and DNS server settings.
- Monitor DNS and ICMP traffic for unusual patterns.
- Investigate potential malicious activity if additional evidence suggests an attack.
- Consider implementing redundant DNS services to improve availability.

## 6. Tools and Skills Demonstrated

**Tool Used:**
- tcpdump – Command-line network packet analysis tool.

**Skills Demonstrated:**
- Network Traffic Analysis
- DNS Troubleshooting
- ICMP Packet Analysis
- UDP Protocol Fundamentals
- Port and Service Identification
- Network Troubleshooting
- Cybersecurity Incident Investigation
- Technical Reporting

## 7. Learning Outcomes

Through this project, I developed practical knowledge of how to investigate network connectivity problems using packet analysis.

I learned how DNS and ICMP protocols work together during network communication, how to identify unreachable services, and how to interpret packet-level error messages to investigate potential network issues.

---

**Project Type:** Network Traffic Analysis and Incident Investigation

**Organization:** Educational Case Study

**Author:** Sukhjit Singh
