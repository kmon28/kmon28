# Security Engineering Portfolio

> **Hands-on security operations and engineering:** building evidence-driven labs that connect endpoint telemetry, network traffic, identity systems, threat detection, and incident investigation.

![SOC Operations](https://img.shields.io/badge/Focus-SOC_Operations-2874A6?style=flat-square)
![Detection Engineering](https://img.shields.io/badge/Focus-Detection_Engineering-4B5563?style=flat-square)
![Active Directory](https://img.shields.io/badge/Windows-Active_Directory-2874A6?style=flat-square)
![Wireshark](https://img.shields.io/badge/Network-Wireshark-1679A7?style=flat-square)
![Portfolio](https://img.shields.io/badge/Portfolio-2_Documented_Projects-218838?style=flat-square)

### SOC Operations · Detection Engineering · IAM · Network Security · Cloud Security

I build and document practical security projects around **SIEM analysis, Windows/Active Directory security, network traffic analysis, identity monitoring, threat hunting, incident investigation, and security engineering**.

**My workflow:** collect telemetry → establish a baseline → detect → validate → investigate → remediate → verify → document.

## Featured Projects

### 🛡️ [Windows SOC Detection & Threat Hunting Lab](https://github.com/kmon28/Windows-SOC-Detection-Lab)

**Splunk Enterprise · Sysmon · Windows Server 2022 · Active Directory · SPL · Sigma · MITRE ATT&CK**

An enterprise-style Windows security monitoring lab combining endpoint and authentication telemetry with detection engineering and investigations. The documented work covers process and authentication analysis, threat-hunting workflows, identity monitoring, and Windows security controls.

**Explore:** [Repository](https://github.com/kmon28/Windows-SOC-Detection-Lab) · [Incident report](https://github.com/kmon28/Windows-SOC-Detection-Lab/blob/main/incident-reports/IR-001-encoded-powershell.md) · [Detection catalog](https://github.com/kmon28/Windows-SOC-Detection-Lab/blob/main/docs/detection-catalog.md) · [ATT&CK mapping](https://github.com/kmon28/Windows-SOC-Detection-Lab/blob/main/docs/mitre-attack.md)

### 🌐 [Network Traffic Analysis & Active Directory Investigation](https://github.com/kmon28/Network-Traffic-Analysis-Lab)

**Wireshark · TCP/IP · DNS · Kerberos · LDAP · SMB2 · VirtualBox · Windows Firewall**

Investigated real traffic generated inside an isolated Active Directory lab. Validated an **ICMP connectivity failure and subnet-scoped firewall remediation**, resolved a VM packet-capture visibility limitation through NIC tracing, documented expected Windows domain protocol behavior, and examined TCP/9997 SYN retransmissions without assuming malicious activity.

**Evidence:** 10 Wireshark screenshots and an ICMP PCAPNG, linked from the project README.

**Explore:** [Repository and technical write-up](https://github.com/kmon28/Network-Traffic-Analysis-Lab) · [Screenshots](https://github.com/kmon28/Network-Traffic-Analysis-Lab/tree/main/screenshots) · [PCAP](https://github.com/kmon28/Network-Traffic-Analysis-Lab/blob/main/pcaps/ICMP_Firewall_Investigation.pcapng)

## Skills Demonstrated

| Area | Hands-on tools and activities |
|---|---|
| Security monitoring | Splunk Enterprise, Windows Security Events, Sysmon, SPL |
| Detection and investigation | Alert validation, threat hunting, incident documentation, MITRE ATT&CK |
| Windows identity | Active Directory, domain authentication, DNS, Group Policy |
| Network analysis | Wireshark, TCP/IP, DNS, ICMP, Kerberos, LDAP, SMB2 |
| Network troubleshooting | TCP retransmission analysis, packet-capture placement, Windows Firewall |
| Virtual infrastructure | VirtualBox, Windows Server 2022, Windows 10 |

## Engineering Approach

- **Evidence first:** link screenshots, packet captures, queries, and findings whenever available.
- **Separate observation from hypothesis:** do not present a possible explanation as a proven root cause.
- **Show remediation and verification:** document what changed and how the outcome was checked.
- **Write for review:** explain scope, environment, methods, results, and limitations so another analyst can evaluate the work.

## Portfolio Roadmap

| Stage | Project | Status |
|---|---|---|
| Foundation | Windows SOC detection and threat hunting | Documented |
| Foundation | Network traffic analysis and Active Directory investigation | Documented |
| Expansion | Linux security operations, forensics, and automation | Planned |
| Expansion | Firewall, network detection, and incident-response scenarios | Planned |
| Expansion | Azure / Entra ID / cloud identity and security monitoring | Planned |
| Expansion | Container security and detection engineering | Planned |

> **Scope note:** These are controlled personal lab exercises, not production security engagements. Planned projects are not presented as completed work. Findings and evidence limitations are documented in the individual repositories.
