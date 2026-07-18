1. What is the primary purpose of a SIEM?

A SIEM (Security Information and Event Management) system provides a centralized platform that collects and analyzes security logs from multiple systems. It allows analysts to review evidence from different sources in one location, making it easier to detect, investigate, and respond to security events.

2. Why is log correlation important during an investigation?

Log correlation is important during an investigation because it connects related events from multiple systems. This helps analysts build a clearer timeline of activity, identify patterns, and reduce the time needed to investigate potential security incidents.

3. Explain how several harmless-looking events can become suspicious when viewed together.

Several harmless-looking events can become suspicious when viewed together because the combination of events may reveal a larger pattern of malicious activity. Individual actions may not seem concerning alone, but when correlated with other events, they may indicate that a system or account has been compromised.

4. Why should analysts collect logs from multiple systems instead of relying on only one?

Analysts should collect logs from multiple systems instead of relying on only one because different sources provide different pieces of evidence. Combining these logs helps create a more accurate timeline and allows analysts to make better-informed decisions before determining whether an incident occurred.

5. Imagine a firewall records a connection from an unfamiliar IP address. A minute later, a Windows system records several failed logins followed by a successful login, and shortly afterward an antivirus program detects malware. Based only on these events, what conclusions can you make, and what additional information would you look for before deciding whether this is a security incident?

Based only on these events, we cannot immediately conclude that a malicious attack occurred. However, the combination of an unfamiliar IP address, multiple failed login attempts followed by a successful login, and a malware detection could indicate suspicious activity that requires further investigation.

Before determining whether this is a security incident, I would review additional evidence such as authentication logs, login locations, timestamps, user activity, the reputation of the IP address, network traffic, and the malware detection details. The goal would be to identify patterns and gather enough evidence before making a final determination.
