# OS Hardening Techniques

## Project Overview

This project is based on a cybersecurity training exercise. The goal was to investigate suspicious website activity, understand network traffic, and recommend security improvements.

I used tcpdump logs to understand how a computer communicated with a website and how the browser was redirected to another website.

## Tools Used

- **tcpdump:** Used to capture and review network traffic.
- **Sandbox Environment:** Used to safely investigate suspicious website activity.

## Investigation Tasks

### 1. Network Protocol Identification

Identified HTTP (Hypertext Transfer Protocol) as the protocol used for communication with the website.

### 2. DNS Analysis

Reviewed DNS requests to identify the IP addresses of the websites.

- yummyrecipesforme.com
- greatrecipesforme.com

### 3. TCP Connection Analysis

Reviewed the TCP three-way handshake:

- SYN – Computer requests a connection.
- SYN-ACK – Server responds.
- ACK – Computer confirms the connection.

### 4. HTTP Traffic Analysis

Identified HTTP GET requests used by the browser to request website pages.

### 5. Suspicious Website Redirection

Observed that the browser initially connected to yummyrecipesforme.com and later communicated with greatrecipesforme.com.

This supported the reported website redirection.

## Key Findings

- DNS requests showed two different website addresses.
- TCP connections were successfully established.
- HTTP GET requests were observed.
- The investigation identified a suspicious website redirection.
- A possible brute-force attack against the administrator account was suspected.

## Security Recommendations

- Use strong and unique passwords.
- Enable Multi-Factor Authentication (MFA).
- Limit repeated failed login attempts.
- Monitor administrator login activity.
- Prevent the reuse of default passwords.

## Skills Practiced

- Network Traffic Analysis
- DNS Analysis
- TCP Handshake Analysis
- HTTP Traffic Inspection
- Basic Incident Investigation
- Security Recommendations

## Project Documentation

The PDF report includes the incident summary, tcpdump log analysis, key findings, and security recommendations.

