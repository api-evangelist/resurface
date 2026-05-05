---
title: "40 Infosec Metrics Organizations Should Track"
url: "https://graylog.org/post/40-infosec-metrics-organizations-should-track/"
date: "Wed, 29 Apr 2026 13:00:06 +0000"
author: "Jeff Darrington"
feed_url: "https://graylog.org/feed/"
---
<p>In today’s data-driven world, CISOs and senior leadership need to prove that their security programs mitigate risk. Just like grades theoretically quantify how well students understand material their teachers present, cybersecurity metrics quantify your security controls’ effectiveness. As the threat landscape becomes more complex, security teams struggle to identify the metrics that best showcase their value.<br />
As your security operations center (SOC) starts monitoring security posture more purposefully, these 40 infosec metrics can help you prove your program’s value and identify areas of improvement.</p>
<p>&nbsp;</p>
<h2>1. Mean Time to Detect (MTTD)</h2>
<p>MTTD measures the average time it takes to identify a security incident after it occurs. By tracking this metric, you have insight into whether you need to improve your security alerts to respond to cyber threats more effectively.</p>
<h2>2. Mean Time to Respond (MTTR)</h2>
<p>MTTR tracks the average time from detection to containment or resolution of a security incident. By monitoring this incident management metric, you can determine whether you need to update your incident response processes.</p>
<h2>3. Mean Time to Recover/Mean Time to Resolve (MTTR)</h2>
<p>This measures the time it takes from initial alert until restoring systems to pre-incident state. While mean time to resolve is often used for broader service failures, mean time to recover is more focused on responding to cybersecurity incidents. By tracking this traditional metric focused on incident response times, you can gain insight into your overall operational resilience.</p>
<h2>4. Mean Time to Contain (MTTC)</h2>
<p>Although often incorporated into the larger mean time to respond metric, incident containment focuses on measuring the average time taken to stop the spread or impact of a security threat after detection. By tracking this incident response plan metric, you can gain insight into how quickly your security team investigates an incident’s root cause and limits its impact.</p>
<h2>5. Mean Time to Acknowledge (MTTA)</h2>
<p>MTTA is the time it takes to begin working on an issue after an alert fires. By tracking this metric, you gain insight into your security team’s workload. For example, if your team has too many false alerts, they may struggle with <a href="https://graylog.org/post/the-importance-of-triage-in-incident-response/">triage and prioritization</a> which means the MTTA will be longer.</p>
<h2>6. Non-Human Network Traffic</h2>
<p>This measures traffic coming from bots or scrapers to determine legitimate from malicious traffic. By measuring non-human network traffic, you gain insights into potential bot or <a href="https://graylog.org/post/how-to-stop-a-ddos-attack/">Distributed Denial of Service (DDoS) attacks</a> against your infrastructure and how well your security team&#8217;s risk management capabilities.</p>
<h2>7. Number of Detected Incidents</h2>
<p>This metric counts how many cyber incidents were identified within a given time period. By monitoring this, you can gain insight into whether threat actors are targeting your systems, how well your detections identify incidents, and look for trends over time.</p>
<h2>8. Incident Severity Levels</h2>
<p>This metric categorizes incidents by their impact to prioritize response, like low, medium, high. This metric provides insight into the types of incidents facing your organization and your security team’s ability to prioritize their activities. By <a href="https://graylog.org/post/leveling-up-security-operations-with-risk-based-alerting/">implementing risk-based alerting</a>, your security team can focus on critical security incidents that have a larger impact on risk, revenue, and reputation.</p>
<h2>9. Patching Cadence</h2>
<p>This measures the percentage of systems with the latest security patches applied after engaging in comprehensive vulnerability scans. By monitoring this security metric, you gain insight into how well your vulnerability management and patch management teams have responded to potential security weaknesses in applications, firmware, software, and operating systems. However, without incorporating threat intelligence to help prioritize activities, this metric is  a basic percentage that fails to help you understand which <a href="https://graylog.org/post/why-patching-isnt-the-ultimate-goal-in-cybersecurity/">vulnerabilities pose actual risks</a> or what assets attackers might focus on.</p>
<h2>10. Patch Latency</h2>
<p>This measures the average time it takes from security patch release to full deployment across the organization. By monitoring this metric, you gain insight into the efficiency of your vulnerability management and patch management processes.</p>
<h2>11. Vulnerability Remediation Time</h2>
<p>This metric tracks how long it takes to fix known vulnerabilities once identified, taking into account when you need to implement a compensating control other than applying a security patch. By tracking this metric, you gain insight into your current attack surface, including end-of-life (EOL) technologies that the manufacturer no longer supports.</p>
<h2>12. Unpatched Critical Vulnerabilities</h2>
<p>This is the number of high-risk vulnerabilities that remain unresolved in the environment. By monitoring this information security risk metric, you gain insight into how well your vulnerability and patch management teams respond to potentially high-risk vulnerabilities.</p>
<h2>13. Percentage of Systems with EOL Software</h2>
<p>This measures how many assets run outdated or unsupported software. These assets often impact your patch compliance rates because the manufacturers no longer provide software updates. By tracking this security metric, you can identify potentially risky assets that either require replacement or compensating controls.</p>
<h2>14. Phishing Click Rates</h2>
<p>This metrics tells you the percentage of users who clicked on simulated or real phishing emails. By monitoring this metric, you can identify trends around your cybersecurity awareness program’s effectiveness.</p>
<h2>15. Phishing Report Rate</h2>
<p>This metric tells you the proportion of users who report phishing emails instead of interacting with them. By monitoring this metric, you can track your workforce members’ ability to take proactive steps to mitigate risk.</p>
<h2>16. Security Awareness Training Completion Rates</h2>
<p>This metric tracks the percentage of users who completed required security training. By tracking this metric, you can prove to your auditors that you meet the cybersecurity training requirements set out by most compliance standards and your organization&#8217;s commitment to creating a security culture across all lines of business.</p>
<h2>17. User Privilege Violations</h2>
<p>This metric counts how often users access systems or data beyond their authorization. By tracking this metric, you gain insight into how well your organization manages<a href="https://graylog.org/post/centralized-log-management-for-access-monitoring/"> user access</a> to ensure compliance with the principle of least privilege.</p>
<h2>18. Number of Privileged Accounts</h2>
<p>This metric counts the total number of accounts with elevated access to critical systems. By monitoring this metric, you can gain insight into whether you have the appropriate monitoring controls for these high-risk accounts and ensure you limit how many you have as much as possible.</p>
<h2>19. Privileged Account Activity Rate</h2>
<p>This measures how often people or services use or access privileged accounts. By monitoring this metric, you can gain insight into typical activity and set baselines which enables you to identify anomalies that can indicate potentially compromised accounts.</p>
<h2>20. Failed Login Attempts</h2>
<p>This metric counts the number of unsuccessful attempts to log in to systems or applications. By monitoring this activity, you gain insight into potential attacks targeting usernames or weak passwords, like <a href="https://graylog.org/post/what-is-credential-stuffing/">credential stuffing attacks</a>.</p>
<h2>21. Account Lockout Events</h2>
<p>This metric is the number of accounts temporarily disabled due to failed login thresholds. By correlating this data with other information, like failed login attempts or user privilege violations, enables your security team to trace the root cause of potential credential based attacks.</p>
<h2>22. Unmanaged Devices Connected to Networks</h2>
<p>This metric refers to the number of devices that are either unauthorized or, if authorized, have no responsible party listed. By tracking this metric, you gain insight into your organization’s ability to <a href="https://graylog.org/post/challenges-with-cybersecurity-asset-identification-and-management/">manage and identify assets</a>, correlating to other security activities like patching vulnerabilities and securing networks.</p>
<h2>23. Endpoint Detection Coverage</h2>
<p>This measures the percentage of endpoints monitored by EDR or antivirus tools. By tracking this metric, you gain insight into overall <a href="https://graylog.org/post/monitoring-endpoint-logs-for-stronger-security/">endpoint security</a> with the ability to identify <a href="https://graylog.org/post/destructive-malware-threat-detection-and-incident-response/">destructive malware</a> and <a href="https://graylog.org/post/detecting-preventing-ransomware-through-log-management/">mitigate ransomware</a> risks.</p>
<h2>24. Malware Detection Rate</h2>
<p>This metric is the number of malware instances detected over a defined time period. By monitoring this metric, you gain insight into how well your security solutions mitigate malicious code risks, including malware and ransomware.</p>
<h2>25. Endpoint Compromise Rate</h2>
<p>This metric expands on the malware detection rate to track the rate of infections or breaches affecting endpoint devices. Typically, this monitoring includes analyzing processes, network connections, file modifications, and user activities that indicate a compromise. It provides insight into potential remote access to and takeover of devices, including servers and laptops.</p>
<h2>26. Firewall Rule Violations</h2>
<p>This metric counts the number of attempts to bypass or exploit misconfigured firewall policies. By monitoring this metric, you gain insight into how well your firewall rules mitigate risks. For example, if your firewall repeatedly blocks access from the same known malicious IP-address, it might indicate attackers trying to gain unauthorized access to the network.</p>
<h2>27. Intrusion Attempts Blocked</h2>
<p>This measures how many unauthorized access attempts were detected and prevented. An <u>intrusion detection</u> system provides insight into potential attacks targeted against your networks. By tracking this metric, you can see trends over time around how well your systems mitigate risk and correlate this data with other information that your environment generates to design detections.</p>
<h2>28. Data Loss Prevention (DLP) Alerts</h2>
<p>This metric tracks the number of alerts triggered by potential data exfiltration attempts. If you use a DLP tool, this metric provides insight into risky sensitive data sharing activities that can indicate malicious or accidental insider threats, including activities like uploading to suspicious domains, accessing with suspicious applications, or saving to removable drives.</p>
<h2>29. Encrypted Traffic Percentage</h2>
<p>This metric is the percentage of network traffic transmitted using encryption protocols. Since encrypting data-in-transit is a fundamental security control, this metric provides insight into how well the organization is protecting data transmissions and provides insight into areas of improvement.</p>
<h2>30. Third-Party Risk Score</h2>
<p>This metric assesses partner or vendor risk based on their security posture, often by collecting audit reports and security questionnaires. By monitoring third-party risk, you can reduce the likelihood of a vendor data breach compromising your systems, networks, or data.</p>
<h2>31. Shadow IT Incidents</h2>
<p>This metrics tracks the number of unauthorized apps or services used by employees. By monitoring this metric, you gain insight into potential risks that arise when people download applications or services to their work computers or use personal cloud services for completing work tasks. The fewer shadow IT incidents you have, the better you are managing your attack surface.</p>
<h2>32. Security Policy Violations</h2>
<p>This measures how often users breach internal security policies. As part of your security program, your employees should read your corporate security policies so that they understand their responsibilities. By monitoring this metric, you gain insight into whether you need to provide additional training around cyber hygiene, like using corporate devices for leisure activities or creating strong passwords.</p>
<h2>33. Compliance Audit Pass Rate</h2>
<p>This metric is the percentage of audits passed without critical findings related to security controls. Since your audits provide third-party attestation over your security posture, any critical findings signal an issue that you must address. By monitoring this metric, you can identify trends around your security program’s effectiveness and your ability to protect sensitive information.</p>
<h2>34. False Positive Rate in Alerts</h2>
<p>This metric reveals the percentage of security alerts that are <a href="https://graylog.org/post/a-new-way-forward-for-the-soc/">incorrectly flagged as threats</a>. Often, security teams struggle to build high fidelity alerts that capture actual threats, often leading them to tune the alerts in ways they fail to identify real threats. By monitoring this metric, you can identify whether your security team is focused on actual threats or spends too much time investigating false positives.</p>
<h2>35. Number of Open Security Tickets</h2>
<p>Correlated to the false positive rate, this metric counts the number of unresolved security-related issues in the queue. After investigating the alert and realizing it was not a real threat, your security team may move on to new issues and forget to close out the tickets. By monitoring this metric, you have insight into whether all incidents have been resolved and whether the team is following the processes that align to your security objectives.</p>
<h2>36. Backup Success Rate</h2>
<p>This metric tracks how often backup jobs complete successfully without errors. Since backups are the key to a successful incident recovery, you should ensure that you understand how often your team completes backups and whether you can trust these backups if you need to restore critical systems.</p>
<h2>37. Incident Cost Estimate</h2>
<p>This metric calculates the real or estimated financial impact of security breaches or incidents. When trying to estimate the potential cost of a security incident, you should consider how it would impact critical systems and sensitive data while looking at the effectiveness of your current risk mitigations. Using this metric, you can make informed decisions around resource allocation and budgeting.</p>
<h2>38. Ransomware Attempt Rate</h2>
<p>This metric tracks the frequency of attempted ransomware attacks over time. Security teams can use various detections to identify attempted ransomware attacks, including signatures with information like IP addresses, behaviors like replacing multiple files with encrypted versions, or anomalous network traffic. By monitoring this metric, you gain insight into your security tools’ effectiveness.</p>
<h2>39. Threat Coverage</h2>
<p>This calculates a percentage that indicates how well your security tools <a href="https://graylog.org/resources/threat-coverage-widget/">respond to different threat types</a>. For example, by mapping Sigma rules to tactics and techniques in the MITRE ATT&amp;CK Framework, you can gain insight into potential gaps. By monitoring this metric, you can see trends over time that show how your security program has matured.</p>
<h2>40. Undocumented or Unmanaged Application Programming Interfaces (APIs)</h2>
<p>This metric identifies the number of <a href="https://graylog.org/post/why-api-discovery-is-critical-to-security/">shadow or deprecated APIs</a> that can potentially expose sensitive data. As attackers increasingly target APIs, discovering and monitoring them enables organizations to implement the appropriate <a href="https://graylog.org/products/api-security/">security controls</a>. By tracking this metric, you can identify trends over time that show how well you mitigate risk or areas for improvement.</p>
<h2>Graylog Security: Visibility to Improve InfoSec Metric Monitoring</h2>
<p>Built on the Graylog Platform, <a href="https://www.graylog.org/products/security/">Graylog Security</a> gives you the features and functionality of a SIEM while eliminating the complexity and reducing costs. With our easy to deploy and use solution, you get the combined power of centralized log management, data enrichment and normalization, correlation, threat detection, incident investigation, anomaly detection, and reporting.</p>
<p>With Graylog’s prebuilt content, you don’t have to worry about choosing the server log data you want because we do it for you. <a href="https://www.graylog.org/features/illuminate/">Graylog Illuminate</a> content packs automate the visualization, management, and correlation processes for you.</p>
<p>To see how Graylog can help you improve your security program and help you manage APTs more effectively, <a href="https://graylog.org/contact-info/">contact us today.</a></p>
<p>The post <a href="https://graylog.org/post/40-infosec-metrics-organizations-should-track/">40 Infosec Metrics Organizations Should Track</a> appeared first on <a href="https://graylog.org">Graylog</a>.</p>
