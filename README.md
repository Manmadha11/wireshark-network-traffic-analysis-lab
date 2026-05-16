# Wireshark Network Traffic Analysis Lab

### Packet-Level Network Investigation and Traffic Analysis using Wireshark

---

## Overview

This project demonstrates practical
network traffic investigation
using Wireshark within a controlled
cybersecurity lab environment.

The investigation focuses on analyzing:

- DNS traffic
- HTTP communication
- TCP sessions
- Packet-level communication
- Application-layer traffic
- Suspicious network behavior

The project simulates
real-world SOC investigation workflows
used during:

- Incident response
- Threat hunting
- Network forensics
- Malware traffic analysis
- Security monitoring

The objective of this lab
is to develop practical experience
with packet capture analysis,
traffic filtering,
protocol investigation,
and evidence-based reporting.

---

# Lab Environment

| Component | Purpose |
|---|---|
| Kali Linux | Traffic generation and analysis |
| Wireshark | Packet capture and protocol analysis |
| Browser Traffic | HTTP and DNS communication |
| Terminal Utilities | DNS and network traffic generation |

---

# Tools Used

| Tool | Purpose |
|---|---|
| Wireshark | Packet capture and traffic analysis |
| nslookup | DNS query generation |
| dig | DNS investigation |
| curl | HTTP traffic generation |
| Browser | Web communication simulation |

---

# Investigation Objectives

The primary objectives of this project include:

- Capture live network traffic
- Analyze DNS communication
- Investigate HTTP requests and responses
- Reconstruct TCP communication streams
- Identify suspicious traffic patterns
- Perform packet-level forensic analysis
- Develop practical SOC investigation skills
- Create professional investigation documentation

---

# Investigation Workflow

The project follows a structured
network investigation methodology.

## Phase 1 — Packet Capture

Traffic was captured
using Wireshark
on the active network interface.

Generated traffic included:

- DNS communication
- HTTP requests
- Browser traffic
- Download activity
- TCP sessions

---

## Phase 2 — DNS Traffic Analysis

DNS packets were analyzed
to investigate:

- Domain resolution activity
- DNS requests and responses
- Recursive query behavior
- External DNS communication
- Failed DNS lookups
- NXDOMAIN responses

### Key Skills Demonstrated

- DNS traffic filtering
- Packet inspection
- DNS response analysis
- Threat hunting visibility

---

## Phase 3 — HTTP Traffic Analysis

HTTP communication was analyzed
to inspect:

- Web requests
- HTTP responses
- Download-related traffic
- Application-layer communication
- Browser-generated traffic

### Key Skills Demonstrated

- HTTP protocol analysis
- Web traffic investigation
- Download traffic analysis
- Application-layer visibility

---

## Phase 4 — TCP Stream Reconstruction

TCP sessions were reconstructed
using Wireshark stream analysis.

The investigation included:

- Session reconstruction
- Client-server communication analysis
- Application-layer conversation analysis
- Stream-level traffic inspection

### Key Skills Demonstrated

- TCP stream reconstruction
- Session analysis
- Communication flow investigation
- Packet-level forensic analysis

---

# Project Structure

```text
WIRESHARK-NETWORK-TRAFFIC-ANALYSIS-LAB/
│
├── 00_Project_Summary/
│
├── 01_Environment_Setup/
│
├── 02_Packet_Capture/
│
├── 03_DNS_Analysis/
│   └── dns-analysis.md
│
├── 04_HTTP_Analysis/
│   └── http-analysis.md
│
├── 05_TCP_Stream_Analysis/
│   └── tcp-stream-analysis.md
│
├── 06_Suspicious_Traffic_Analysis/
│
├── 07_Findings_Report/
│
├── README.md
│
├── dns-filter.png
├── dns-queries.png
├── failed-dns.png
├── http-filter.png
├── http-requests.png
├── http-download.png
├── tcp-filter.png
├── tcp-stream.png
└── tcp-conversation.png
```

---

# Packet Analysis Techniques

The investigation included
multiple packet analysis techniques.

| Technique | Purpose |
|---|---|
| DNS Filtering | Investigate domain communication |
| HTTP Filtering | Analyze web traffic |
| TCP Stream Reconstruction | Rebuild communication sessions |
| Packet Inspection | Analyze protocol behavior |
| Traffic Correlation | Investigate communication patterns |

---

# Wireshark Filters Used

## DNS Filter

```text
dns
```

## HTTP Filter

```text
http
```

## TCP Filter

```text
tcp
```

---

# Supporting Evidence

## DNS Traffic Investigation

![DNS Filter](../dns-filter.png)

![DNS Queries](../dns-queries.png)

![Failed DNS Lookup](../failed-dns.png)

---

## HTTP Traffic Investigation

![HTTP Filter](../http-filter.png)

![HTTP Requests](../http-requests.png)

![HTTP Download](../http-download.png)

---

## TCP Stream Investigation

![TCP Filter](../tcp-filter.png)

![TCP Stream](../tcp-stream.png)

![TCP Conversation](../tcp-conversation.png)

---

# Security Relevance

Packet analysis is a critical skill
for SOC analysts,
incident responders,
threat hunters,
and network defenders.

Network traffic investigation
helps security teams:

- Detect malicious communication
- Investigate malware traffic
- Analyze suspicious downloads
- Identify command-and-control activity
- Investigate data exfiltration
- Monitor abnormal communication patterns

Wireshark provides deep visibility
into packet-level network behavior,
making it one of the most important
tools used in cybersecurity operations.

---

# Skills Demonstrated

This project demonstrates practical experience with:

- Packet Capture Analysis
- DNS Investigation
- HTTP Traffic Analysis
- TCP Stream Reconstruction
- Network Traffic Monitoring
- Threat Hunting
- Traffic Filtering
- Protocol Analysis
- Incident Investigation
- Security Analysis
- Evidence Collection
- Technical Documentation

---

# MITRE ATT&CK Relevance

| Technique | Tactic |
|---|---|
| Application Layer Protocol | Command and Control |
| Network Service Discovery | Discovery |
| Data from Network Shared Drive | Collection |
| Exfiltration Over Web Service | Exfiltration |

---

# Key Investigation Findings

The investigation successfully identified:

- DNS communication activity
- HTTP request and response traffic
- TCP session behavior
- Application-layer communication
- Download-related traffic
- External server interaction
- Stream-level communication visibility

The packet capture confirmed
successful traffic monitoring
and protocol-level analysis
within the lab environment.

---

# Future Improvements

Future enhancements may include:

- HTTPS traffic analysis
- Suspicious domain detection
- Malware traffic simulation
- PCAP forensic analysis
- IDS/IPS integration
- Suricata alert analysis
- Zeek log correlation
- Threat intelligence integration

---

# Conclusion

This project successfully demonstrates
practical packet-level traffic investigation
using Wireshark within a cybersecurity lab.

The investigation provided hands-on experience with:

- DNS analysis
- HTTP traffic investigation
- TCP stream reconstruction
- Packet filtering
- Network forensic analysis
- SOC investigation workflows

The project reflects
real-world network investigation techniques
used by SOC analysts
and incident response teams
during cybersecurity operations.
