# Network Incident Report – DDoS Attack Response

## Objective  
This project involved analyzing and responding to a DDoS attack on a fictional multimedia company using the NIST Cybersecurity Framework (CSF). The goal was to produce a clear incident report and outline an improvement plan for future incident prevention and response.

### Skills Learned  
- Understanding and applying the NIST Cybersecurity Framework  
- Incident response planning and documentation  
- Identifying vulnerabilities in firewall configurations  
- Developing network protection strategies  
- Enhancing detection and recovery processes  

### Tools Used  
- Network monitoring tools  
- IDS/IPS systems  
- Firewall configuration management  
- Google Docs (for documentation/report writing)

## Steps  
#### These steps include screenshots taken from the Incident Response Template utilized during the process.

### 1. Summary of the Incident 
- The company experienced a Distributed Denial of Service (DDoS) attack using ICMP packets, disrupting internal services for 2 hours.  
- The attack exposed an unconfigured firewall, allowing malicious traffic into the network.
<img width="707" alt="Screenshot 2025-04-07 at 18 04 36" src="https://github.com/user-attachments/assets/7454c3fe-e9b3-46b8-8f8a-aea309cba1e2" />

  The image shows the summary from the incident report analysis


### 2. Identify (NIST CSF)
- Weakness discovered: Firewall lacked ICMP filtering and rate limiting.  
- Regular network audits recommended to find similar gaps.  
- Access control and firewall configuration needed review.
<img width="701" alt="Screenshot 2025-04-07 at 18 06 43" src="https://github.com/user-attachments/assets/a3d94728-c2c2-4f2c-be21-46d1ce0d0078" />

 The image shows the identify plan from the incident report analysis

### 3. Protect
- A new firewall rule was created to limit incoming ICMP packets.  
- Source IP address verification was implemented to detect spoofed traffic.  
- Staff were reminded of incident handling protocols.
<img width="703" alt="Screenshot 2025-04-07 at 18 07 00" src="https://github.com/user-attachments/assets/46d014fc-6f5a-4db5-b786-27b6bbf2d82e" />

 The image shows the protect plan from the incident report analysis

### 4. Detect 
- Network monitoring tools were introduced to track traffic anomalies.  
- An IDS/IPS was deployed to detect and flag suspicious ICMP traffic.  
- Alerts were configured to notify the team in case of future traffic spikes.
<img width="702" alt="Screenshot 2025-04-07 at 18 07 30" src="https://github.com/user-attachments/assets/ccdd0cea-ad80-4e12-8c2d-6f860a86f45d" />

The image shows the detect plan from the incident report analysis

### 5. Respond
- ICMP packets were blocked immediately during the attack.  
- Non-essential network services were disabled temporarily.  
- The attack was contained and logged for analysis.
<img width="688" alt="Screenshot 2025-04-07 at 18 07 57" src="https://github.com/user-attachments/assets/8fb35970-77ee-4e5c-911b-77cfb84abeba" />

 The image shows the respond plan from the incident report analysis

### 6. Recover
- Critical services were restored after traffic normalized.  
- The team conducted a post-incident review.  
- Recovery procedures were documented and tested.
<img width="690" alt="Screenshot 2025-04-07 at 18 08 18" src="https://github.com/user-attachments/assets/590fb1a2-784f-44cb-8183-373339551328" />

 The image shows the recover plan from the incident report analysis

## Conclusion  
This incident report demonstrates the importance of a proactive cybersecurity approach using the NIST CSF. The organization effectively mitigated a real-time threat and implemented long-term security improvements, including firewall reconfiguration, monitoring tools, and response protocols. Applying this framework helps strengthen resilience and ensures the organization is better prepared for future threats.

## References  
- [Incident Report Template](https://docs.google.com/document/d/14FWNOzxCUK4gLj_sSXEVBVk-BDVkXi18hAWDh0vRgUU/edit?tab=t.0)
- [Applying the NIST CSF](https://docs.google.com/document/d/15yCDbDCOAcJw-LTz2DeCA7UeLRfvsf176T6MA6ku6ok/template/preview)
