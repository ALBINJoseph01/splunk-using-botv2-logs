# splunk-using-botv2-logs
Splunk Dashboard for Comprehensive Log Analysis

This repository contains Splunk dashboard configurations designed to monitor and analyze logs from Botv2 across multiple fields, including Intrusion Detection Systems (IDS), Windows, Syslog, FTP, UDP, TCP, and firewall events.

Features:

* Comprehensive Log Collection: Aggregates log data from diverse sources such as IDS, Windows systems, Syslog servers, FTP transactions, network protocols (UDP/TCP), and firewalls.
  
* Real-Time Monitoring: Provides real-time insights and visualizations into network traffic, security events, and system activities, ensuring timely detection of potential threats.
  
* Custom Dashboards: Includes customizable dashboards tailored for each log source, facilitating quick identification and analysis of security incidents.
  
* Advanced Search & Reporting: Leverages Splunk's powerful search and reporting features to create actionable insights and detailed reports on network security and operational efficiency.
  
* Proactive Alerts: Configured alerts to notify of suspicious activities or anomalies detected in the logs, enhancing incident response capabilities.

Splunk Firewall Log Analysis Dashboard for Botv2

This repository features a Splunk dashboard created to analyze firewall logs from Botv2, providing detailed insights into network security events and traffic patterns.

Dashboard Features:

* Blocked and Allowed Connections: Visualize and differentiate between blocked and allowed firewall connections, offering a clear overview of network security posture.
  
* External Source and Destination IPs: Track and analyze the external IP addresses involved in network traffic, aiding in the identification of potential threats.
  
* Network Traffic Analysis: Monitor network traffic by action, protocol, and app/protocol combinations to understand usage patterns and detect anomalies.
  
* Blocked Incoming Traffic by Destination Port: Identify which destination ports are most frequently targeted by blocked incoming traffic, highlighting potential attack vectors.
  
* Incoming Traffic by App/Protocol: Analyze incoming traffic based on application and protocol, providing insights into network service usage and potential vulnerabilities.
  
* Top Countries and Sources by Blocked Connections: Discover the top countries and source IPs responsible for blocked connections, helping to identify geographic patterns in attack attempts.
  
* Top Applications by Blocked Connections: Identify the top applications targeted by blocked connections, allowing for better application-level security management.
  
screenshot of the dashboard
  
![Screenshot_17-6-2024_115434_127 0 0 1](https://github.com/user-attachments/assets/51bfc8bf-2f81-4558-a36a-06d1c54df86c)



Splunk IDS/IPS Intrusion Detection Dashboard for Botv2

This repository features a Splunk dashboard designed to analyze IDS/IPS logs from Botv2, offering a detailed view of intrusion detection and security events.

Dashboard Features:

* Allowed and Blocked Intrusion Attempts: Track and visualize both allowed and blocked intrusion attempts, providing insights into the effectiveness of your intrusion detection/prevention system.
  
* Severity-Based Alerts: Monitor and categorize alerts by severity (high, medium, low) to prioritize security responses and address the most critical threats first.
  
* Intrusion Signatures and Attacks: Analyze intrusion signatures to identify specific attack patterns and track intrusion attempts from external sources.
  
* Intrusion Alerts by Signature and Severity: Gain detailed insights into intrusion alerts, organized by signature and severity, to understand the types and seriousness of threats targeting your network.
  
* Scanning Activity: Detect and respond to scanning activities by identifying multiple attacks originating from the same source, highlighting potential reconnaissance behavior.

screenshot of the dashboard

![Screenshot_18-6-2024_11305_127 0 0 1](https://github.com/user-attachments/assets/e818ee7a-4f77-48a8-aa20-d69c93eb60e6)

Splunk Windows Log Analysis Dashboard for Botv2
This repository features a Splunk dashboard created to analyze Windows logs from Botv2. It provides detailed insights into various security events and user activities.

Dashboard Features
* Locked Out Accounts:Monitor and visualize accounts that have been locked out due to multiple failed login attempts, helping to identify potential security issues or malicious activity.

* Privilege Escalations:Track and analyze instances of privilege escalation to detect unauthorized attempts to gain higher-level access within the system.
  
* Failed Logons:Identify and review failed login attempts to assess potential security threats or issues with authentication mechanisms.
  
* Successful Logons:Monitor successful login events to track user activity and identify patterns or anomalies in access behavior.
  
* Created Actions:Visualize and analyze actions related to the creation of new accounts or objects within the system.
  
* Deleted Actions:Track and review actions involving the deletion of accounts or objects, providing insights into potential unauthorized changes or deletions.
  
* Modified Actions:Monitor modifications to accounts or system objects, helping to identify changes that may impact security or operational integrity.
  
* Rare AD Domains in Logs:Identify and review logs for rare Active Directory (AD) domains, which may indicate unusual or potentially suspicious activities.
  
* User Account Changes:Analyze changes made to user accounts, including modifications to account settings or attributes, to detect unauthorized alterations.
  
* Logon by User:Track and visualize logon events on a per-user basis to understand access patterns and identify unusual logon behavior.
  
* Logon Success/Failure:Review both successful and failed logon attempts to assess authentication success rates and detect potential security concerns.

  screenshot of the dashboard

![Screenshot_25-6-2024_104722_127 0 0 1](https://github.com/user-attachments/assets/5ccddbe9-7211-40c0-aad1-ef56f0dfaa01)




