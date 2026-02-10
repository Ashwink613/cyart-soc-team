### Incident Classification Overview



In a Security Operations Center (SOC), incidents must be classified accurately to ensure proper response, escalation, and reporting. Classification helps analysts understand the nature of the threat, affected assets, and required response actions.



This document classifies common security incidents using standardized frameworks such as MITRE ATT\&CK, ensuring consistency across investigations.



###### Incident Classification Table



Incident Type	   Description	                           MITRE Technique	Category

Phishing	  Malicious email containing a suspicious link	T1566	Social Engineering

Brute Force	  Multiple authentication attempts on an accountT1110	Credential Access

Ransomware	  File encryption affecting system availability	T1486	Impact

Web Exploitation  Exploitation of vulnerable web service 	T1190	Initial Access

Insider Threat	  Unauthorized access by a legitimate user	T1078	Privilege Abuse

###### 

###### Contextual Metadata Example



Each incident is enriched with contextual metadata to support investigation and response.



###### Example:



Incident Type: Brute Force  

Affected System: Server-X  

Source IP: 192.168.1.100  

Time Detected: 2026-02-04 14:10  

User Account: admin  

Indicator of Compromise (IOC): Repeated failed login attempts  





This metadata enables SOC analysts to quickly understand the scope and severity of an incident.



###### Outcome



Standardized incident classification improves incident handling efficiency, reduces response time, and ensures accurate communication between SOC tiers and stakeholders.

