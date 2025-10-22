Security onion is a free, open-source platform for **network security monitoring (NSM), log management, and intrusion detection**. It provides a comprehensive suite of tools designed to help analysts detect, investigate, and respond to cyber threats in real time.

This OS is like the Kali Linux of network monitoring. It comes preconfigured with tools such as:
- zeek: network traffic analysis
- suricata: intrusion detection and prevention
- Elastic stack: log management and analysis

**Network Security Monitoring (NSM)**  
- **Packet Capture and Analysis**: Tools like **Zeek** analyze network traffic for anomalies or suspicious activity.  
- **Intrusion Detection Systems (IDS)**: **Suricata** performs real-time deep packet inspection to identify malicious activity.
**Log Management and Analysis**  
- **Collects and aggregates logs**: from endpoints, firewalls, servers, and other devices for network visibility.  
- **Elastic Stack**: enables querying, visualizing, and analyzing logs in an intuitive dashboard.
**Incident Response**  
- **Alerts and Correlation**: Generates alerts for suspicious activities, helping analysts prioritize threats.  
- **Threat Hunting**: Analysts can proactively search for signs of compromise using enriched datasets.

Security Onion enhances an organization’s security posture with advanced detection and monitoring capabilities:
- **Proactive Threat Detection**: Identifies threats before they escalate and cause damage, if the tools are properly deployed.
- **Comprehensive Visibility**: Aggregates network and endpoint data for a holistic view.
- **Incident Response Readiness**: Equips analysts with tools for quick investigation and response.
The security onion servers should be isolated from the rest of the network to minimize the risk of compromise

After booting the OS, we need to choose the configuration:
- hostname: project-x-sec-work
- IPv4 static address: 10.0.0.103/24
- default gateway: 10.0.0.1
- default DNS servers: 8.8.8.8, 8.8.4.4
- DNS search domain: corp.project-x-dc.com
After the GUI is ready, i can use the terminal to change the root password: sudo passwd root
=> @password123!


