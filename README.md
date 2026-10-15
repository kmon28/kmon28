# Security Engineering Portfolio

**SOC Operations · Detection Engineering · Windows / Active Directory · Network Security**

I build hands-on security labs that turn telemetry into **validated findings, documented investigations, and practical remediation**. My work spans Splunk/Sysmon monitoring, Windows identity security, and packet-level network analysis.

![Splunk](https://img.shields.io/badge/SIEM-Splunk-4B5563?style=flat-square)
![Sysmon](https://img.shields.io/badge/Endpoint-Sysmon-2874A6?style=flat-square)
![Active Directory](https://img.shields.io/badge/Identity-Active_Directory-2874A6?style=flat-square)
![Wireshark](https://img.shields.io/badge/Network-Wireshark-1679A7?style=flat-square)

## Featured Projects

### [Windows SOC Detection & Threat Hunting Lab](https://github.com/kmon28/Windows-SOC-Detection-Lab)

**Splunk Enterprise · Sysmon · Windows Server 2022 · Active Directory · SPL · MITRE ATT&CK**

Built an isolated Windows security monitoring environment to investigate endpoint and authentication events, develop detections, examine suspicious behavior, and document findings. Includes incident reporting, detection documentation, and ATT&CK mapping.

**[Project overview](https://github.com/kmon28/Windows-SOC-Detection-Lab)** · [Incident report](https://github.com/kmon28/Windows-SOC-Detection-Lab/blob/main/incident-reports/IR-001-encoded-powershell.md) · [Detection catalog](https://github.com/kmon28/Windows-SOC-Detection-Lab/blob/main/docs/detection-catalog.md)

### [Network Traffic Analysis & Active Directory Investigation](https://github.com/kmon28/Network-Traffic-Analysis-Lab)

**Wireshark · TCP/IP · DNS · Kerberos · LDAP · SMB2 · Windows Firewall**

Analyzed Active Directory network communications and investigated connectivity problems. Used packet evidence to validate a **subnet-scoped ICMP firewall fix**, improved VM-to-VM capture visibility through VirtualBox NIC tracing, and examined TCP/9997 retransmissions without claiming an unverified root cause.

**[Project overview](https://github.com/kmon28/Network-Traffic-Analysis-Lab)** · [10 evidence screenshots](https://github.com/kmon28/Network-Traffic-Analysis-Lab/tree/main/screenshots) · [ICMP PCAP](https://github.com/kmon28/Network-Traffic-Analysis-Lab/blob/main/pcaps/ICMP_Firewall_Investigation.pcapng)

### [Kali Linux Security Assessment & Defensive Investigation Lab](https://github.com/kmon28/Kali-Linux-Security-Assessment-Lab)

**Kali Linux · Nmap · LDAP · SMB · Active Directory · Windows Event 4625**

Performed controlled reconnaissance and identity-security analysis in a VirtualBox AD lab. Verified **SMB signing required** on DC02, reviewed LDAP and privileged-group information, correlated a deliberate failed SMB authentication attempt with Windows Security Event **4625**, and documented a TCP/445 **filtered** retest after hardening.

**[Project walkthrough](https://github.com/kmon28/Kali-Linux-Security-Assessment-Lab)** · [Investigation report](https://github.com/kmon28/Kali-Linux-Security-Assessment-Lab/blob/main/reports/IR-001-smb-authentication-and-hardening.md) · [Evidence screenshots](https://github.com/kmon28/Kali-Linux-Security-Assessment-Lab/tree/main/screenshots) · [Study notes](https://github.com/kmon28/Kali-Linux-Security-Assessment-Lab/blob/main/docs/study-notes-and-interview-review.md)

## Technical Skills Demonstrated

| Focus | Technologies and practical work |
|---|---|
| SIEM & endpoint telemetry | Splunk Enterprise, SPL, Sysmon, Windows Security Events |
| Detection & investigation | Threat hunting, alert analysis, incident documentation, MITRE ATT&CK |
| Identity & Windows security | Active Directory, Kerberos, LDAP, DNS, Group Policy, Windows Event 4625 |
| Network analysis | Wireshark, Nmap, TCP/IP, ICMP, SMB2, TCP retransmissions, packet capture |
| Lab infrastructure | Windows Server 2022, Windows 10, VirtualBox, Windows Firewall |

## How I Work

**Collect → Baseline → Detect → Validate → Investigate → Remediate → Verify → Document**

I distinguish observed evidence from hypotheses, record limitations, and prioritize reproducible investigations over unsupported conclusions. Each repository contains the technical details and supporting artifacts.

## Next Areas of Development

**Linux security and automation · Network detection and incident response · Azure/Entra ID and cloud security**

*These are planned areas of development, not completed projects. All published investigations are controlled lab exercises, not production incidents.*
