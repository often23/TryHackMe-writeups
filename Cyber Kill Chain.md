🔐 [Cyber Kill Chain] - TryHackMe

🧠 Room Overview
In this room, we will learn about the Cyber ​​Kill Chain proposed by Lockheed Martin. By visualizing the seven phases of an attack that an attacker takes against a target, we aim to understand where defenders can detect and prevent attacks.

Objectives:
- Understand the overall attack phases
- Consider defensive measures for each phase
- Use this knowledge in alert response and escalation decisions in SOC operations.

 💻 Environment and Tools
- TryHackMe AttackBox (Browser-Based)
- Tools Used:
- CyberChef (Decoding)
- Wireshark (Packet Analysis)
- VirusTotal (IOC Matching)
- MITRE ATT&CK (Supplementary Reference)

🚀 Procedure
- Understanding the Seven Phases of the Kill Chain
- Reconnaissance
- Weaponization
- Delivery
- Exploitation
- Installation
- Command & Control
- Actions on Objectives
- Analyze traces of each phase
- Confirm the delivery phase using packet capture
- Detect the installation phase by modifying the registry or installing a backdoor
- Trace the kill chain using exercises
- Classify phases using attack logs
- Identify defense points and consider countermeasures

🏁 Flags
- User flag: THM{kill_chain_detected}
- Root flag: None (focus on concepts and analysis)

💬 Thoughts
- Lessons learned:
- Attacks progress in stages, so it's important to be aware of the phases that allow for early detection.
- In the SOC, determining the "phase" changes the response priority and escalation destination.
- Combining the Kill Chain with MITRE ATT&CK allows for more practical analysis.
- Observations/Areas for improvement:
- I want to improve my ability to quickly extract indicators (IOCs) for each phase from logs.
