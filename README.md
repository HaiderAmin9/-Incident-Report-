# Incident Report Analysis: DDoS Attack on Multimedia Company

## Summary of Security Event

As part of my hands-on experience during the Google Cybersecurity Certification program, I analyzed a Distributed Denial of Service (DDoS) attack that occurred at a multimedia company. This attack compromised the company's internal network for two hours by flooding it with ICMP packets, which disrupted all network services. The incident was mitigated by blocking incoming ICMP packets, taking non-critical services offline, and restoring critical network operations.

## NIST Cybersecurity Framework (CSF) Application

### 1. Identify

- **Risk Identification**: 
  - The DDoS attack exploited a firewall vulnerability, allowing a flood of ICMP packets to overwhelm the network.
  - Affected systems included internal network devices and servers, which were rendered inaccessible due to the attack.
- **Security Gaps**:
  - The unconfigured firewall was identified as a significant security gap, which was subsequently addressed.

### 2. Protect

- **Immediate Protection Measures**:
  - A new firewall rule was implemented to limit the rate of incoming ICMP packets.
  - Source IP address verification was enabled on the firewall to detect and block spoofed IP addresses.
  - Policies and procedures were updated to ensure proper configuration of security controls and regular network audits.
- **Training and Awareness**:
  - IT staff were trained on the importance of firewall configurations and the implementation of advanced security measures.
  - Awareness programs were initiated to enhance the team's understanding of network security best practices.

### 3. Detect

- **Monitoring and Detection Tools**:
  - Network monitoring software was deployed to identify and alert the team of abnormal traffic patterns in real-time.
  - An Intrusion Detection System/Intrusion Prevention System (IDS/IPS) was implemented to filter suspicious ICMP traffic.
  - Logging mechanisms were improved to capture detailed network traffic information for forensic analysis.

### 4. Respond

- **Response Plan**:
  - A comprehensive response plan was developed to ensure quick isolation of affected systems and containment of future attacks.
  - Clear communication channels were established within the security team to facilitate coordinated responses.
  - A post-incident analysis was conducted to assess the attack's impact and refine the organization's response strategy.
- **Mitigation Steps**:
  - Procedures were put in place to take critical systems offline safely, minimizing operational impact during future incidents.
  - Regular security drills were scheduled to test the effectiveness of the response plan and identify improvement areas.

### 5. Recover

- **Recovery Actions**:
  - Network services were restored to normal operations after confirming the attack was fully mitigated.
  - Affected systems were rebuilt with updated security configurations to prevent future vulnerabilities.
  - The recovery process and system restoration were communicated to all relevant stakeholders, ensuring transparency.
- **Improvement Strategies**:
  - The organization's disaster recovery plan was reviewed and updated to address the weaknesses identified during the incident.
  - Backup processes were enhanced to ensure quick recovery of critical systems in future incidents.

---

This incident report was developed as part of the practical application of the National Institute of Standards and Technology's Cybersecurity Framework (NIST CSF) during my Google Cybersecurity Certification program. The report underscores the importance of continuous improvement in cybersecurity practices to mitigate emerging threats effectively.
