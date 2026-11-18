# Analyze Traffic with Wireshark Logs

## Project Overview
This project analyzes network traffic using Wireshark logs to identify suspicious activity and possible network attacks.

## Objectives
- Examine network traffic logs.
- Identify unusual TCP activity.
- Understand TCP three-way handshake.
- Investigate possible TCP SYN flood activity.
- Identify network errors and connection issues.

## Tools Used
- Wireshark
- Network traffic logs
- TCP/IP analysis

## Findings
The logs showed repeated TCP SYN packets from `203.0.113.0` to `192.0.2.1`.

The traffic pattern was consistent with a possible TCP SYN flood attack. The logs also contained TCP RST responses and an HTTP 504 Gateway Time-out message.

## TCP Three-Way Handshake
A normal TCP connection uses three steps:

1. SYN – The client requests a connection.
2. SYN-ACK – The server responds.
3. ACK – The client confirms the connection.

In a SYN flood, repeated SYN requests can cause a server to use resources waiting for connections to complete.

## Conclusion
This analysis helped identify unusual TCP traffic and understand how a possible SYN flood can affect network availability.

## Skills Demonstrated
- Network traffic analysis
- Wireshark log examination
- TCP/IP fundamentals
- Identifying suspicious network activity
- Incident documentation
