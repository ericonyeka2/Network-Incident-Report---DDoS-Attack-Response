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

*Screenshots & Documentation*  
- Add screenshots of the report analysis, configuration updates, or monitoring setup here.  
(You can use tools like Imgur or GitHub image embedding)

---

Let me know once you’ve added your own screenshots or filled in specific report content, and I can help you polish the final version.
