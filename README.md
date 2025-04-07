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

*Ref 1: Summary of the Incident*  
- The company experienced a Distributed Denial of Service (DDoS) attack using ICMP packets, disrupting internal services for 2 hours.  
- The attack exposed an unconfigured firewall, allowing malicious traffic into the network.

*Ref 2: Identify (NIST CSF)*  
- Weakness discovered: Firewall lacked ICMP filtering and rate limiting.  
- Regular network audits recommended to find similar gaps.  
- Access control and firewall configuration needed review.

*Ref 3: Protect*  
- A new firewall rule was created to limit incoming ICMP packets.  
- Source IP address verification was implemented to detect spoofed traffic.  
- Staff were reminded of incident handling protocols.

*Ref 4: Detect*  
- Network monitoring tools were introduced to track traffic anomalies.  
- An IDS/IPS was deployed to detect and flag suspicious ICMP traffic.  
- Alerts were configured to notify the team in case of future traffic spikes.

*Ref 5: Respond*  
- ICMP packets were blocked immediately during the attack.  
- Non-essential network services were disabled temporarily.  
- The attack was contained and logged for analysis.

*Ref 6: Recover*  
- Critical services were restored after traffic normalized.  
- The team conducted a post-incident review.  
- Recovery procedures were documented and tested.

## Conclusion  
This incident report demonstrates the importance of a proactive cybersecurity approach using the NIST CSF. The organization effectively mitigated a real-time threat and implemented long-term security improvements, including firewall reconfiguration, monitoring tools, and response protocols. Applying this framework helps strengthen resilience and ensures the organization is better prepared for future threats.

## References  
- [Incident Report Template – Google Docs](https://docs.google.com/document/d/1EnieOKYJyKGsVff5Gg-3-dVwrHrZ2m8Hig6tVpfKqyg/template/preview?resourcekey=0-eb5t-d69zTPLEGthIpVlXw)  
- [Example Analysis – Google Docs](https://docs.google.com/document/d/15yCDbDCOAcJw-LTz2DeCA7UeLRfvsf176T6MA6ku6ok/template/preview)
