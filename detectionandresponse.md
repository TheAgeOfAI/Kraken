# Incidence response lifeCycle

Event - An observable occurrence on a network, system, or device.

5 W's of an incident

1. who triggered the incident
2. what happened
3. When the incident took place
4. where the incident took place
5. Why the incident occured

computer security incident response team (csirt)

Roles in csirt

1. Security analyst
    The job of the security analyst is to continuously monitor an environment for any security threats. This includes: 
        Analyzing and triaging alerts
        Performing root-cause investigations
        Escalating or resolving alerts 

2. Technical lead
    manage all of the technical aspects such as,
    applying software patches or updates

3. Incident coordinator

National Institute of Standards and Technology (NIST) Incident Response Lifecycle

1. Preparation
2. Detection and Analysis
3. Containment, Eradication, and Recovery
4. Post-incident activity


security operations center (SOC)

SOC is an organizational unit dedicated to monitoring networks, systems, and devices for security threats or attacks.

### Tier 1 SOC analyst

    The first tier is composed of the least experienced SOC analysts who are known as level 1s (L1s). They are responsible for:

1. Monitoring, reviewing, and prioritizing alerts based on criticality or severity
2. Creating and closing alerts using ticketing systems
3. Escalating alert tickets to Tier 2 or Tier 3

### Tier 2 SOC analyst

    The second tier comprises the more experienced SOC analysts, or level 2s (L2s). They are responsible for: 

1. Receiving escalated tickets from L1 and conducting deeper investigations
2. Configuring and refining security tools
3. Reporting to the SOC Lead

### Tier 3 SOC lead
    The third tier of a SOC is composed of the SOC leads, or level 3s (L3s). These highly experienced professionals are responsible for:

1. Managing the operations of their team
2. Exploring methods of detection by performing advanced detection techniques, such as malware and forensics analysis
3. Reporting to the SOC manager

### SOC manager 
    The SOC manager is at the top of the pyramid and is responsible for: 

1. Hiring, training, and evaluating the SOC team members
2. Creating performance metrics and managing the performance of the SOC team
3. Developing reports related to incidents, compliance, and auditing
4. Communicating findings to stakeholders such as executive management 

Incidence response plan
    a document that outlines the procuderes to take in each step of incidence response.

    Elements of Incidence response plan
        1. Incidence response procedure
        2. System Information
        3. Other documents

Types of Tools:

1. Detection and management tools
2. Documentation tools
3. Investigation tools

### Intrusion Detection System (IDS)
    An intrusion detection system (IDS) is an application that monitors system activity and alerts on possible intrusions.
    Examples of IDS tools include Zeek, Suricata, Snort®, and Sagan

### Intrusion Prevention System (IPS)
    An intrusion prevention system (IPS) is an application that monitors system activity for intrusive activity and takes action to stop the activity.
    Many IDS tools can also operate as an IPS. Tools like Suricata, Snort, and Sagan have both IDS and IPS capabilities.

### Endpoint Detection and Response (EDR)
    Endpoint detection and response (EDR) is an application that monitors an endpoint for malicious activity.
    Tools like Open EDR®, Bitdefender™ Endpoint Detection and Response, and FortiEDR™ are examples of EDR tools.


The three steps of the SIEM process are:
    1. collect and aggregate data,
    2. normalize data,
    3. and analyze data.

Security Orchestration, automation and response
    A collection of applications,tools and workflows that uses automation to respond to security tools.

Network traffic : The amount of data that moves across a network

Network data: Data that's transmitted b/w devices on a network.

Data exfilteration
    Defensive measures
        1. Prevent attack access
        2. Monitor network analysis
        3. Protect accets
        4. Detect and stop the exfilteration

Lateral movement, also called pivoting, describes an attacker exploring a network with the goal of expanding and maintaining their access.  

**Detection** refers to the prompt discovery of security events.
**Analysis** involves the investigation and validation of alerts.

**Threat hunting** is the proactive search for threats on a network.

**Indicators of compromise**(IoCs) are observable evidence that suggests signs of a potential security incident.
    Who and what of an attack.

**Indicators of attack**(IoA) are the series of observed events that indicate a real-time incident.
    Why and how of an attack.

### Pyramid of pain
    Pyramid of pain in the order of easy to hard.
1. Hash values: Hashes that correspond to known malicious files. These are often used to provide unique references to specific samples of malware or to files involved in an intrusion.

2. IP addresses

3. Domain names

4. Network artifacts: Observable evidence created by malicious actors on a network. For example, information found in network protocols such as User-Agent strings. 

5. Host artifacts: Observable evidence created by malicious actors on a host. For example, the name of a file created by malware.

6. Tools: Software that’s used by a malicious actor to achieve their goal.

7. Tactics, techniques, and procedures (TTPs): This is the behavior of a malicious actor. Tactics refer to the high-level overview of the behavior. Techniques provide detailed descriptions of the behavior relating to the tactic. Procedures are highly detailed descriptions of the technique. TTPs are the hardest to detect.

**Crowdsourcing** is the practice of gathering information using public input and collaboration.

### Benifits of Documentation

1. Transparency
    **Chain of custody** is the process of documenting evidence possession and control during an incident lifecycle.

2. Standardization
    **Standards** are references that inform how to set policies.

3. Clarity

