# Playbook for Cat & Box Scenario

### Standard Operating Procedure (Playbook) for Security Incident Response

1. **Initial Detection and Assessment:**
   - The SOC monitors the network, systems, and data for any suspicious activity or potential security incidents.
   - Upon detection of an incident, the SOC initiates the incident response process.

2. **Incident Triage and Classification:**
   - The SOC assesses the severity and impact of the incident.
   - Incidents are classified based on severity levels such as critical, high, medium, or low.

3. **Notification and Escalation:**
   - If the incident is classified as critical or high, The following people are contacted:  
     **Cat is notified _Immediately_**
    - Method: Phone call to both daytime and after-hours numbers.
    - Numbers used: 902 88-1234 & cell 902 77-4321  
    **Misha is notified _Immediately_**
      - Method: Email
      - Address: mesha@box.cat  
    **Misha is notified _Business hours (9AM to 5PM AST)_**
      - Method: Phone call
      - Number: 902 66-9999
       - If Misha is unavailable:
         **Minka is contacted** as the alternate contact person.
         - Method: Phone
         - Number: 902 99-9999

5. **Investigation and Remediation:**
   - Cat coordinates with the SOC to gather detailed information about the incident, including its cause, impact, and potential remediation steps.
   - Cat evaluates the incident and approves appropriate remediation actions.
   - Playbooks and workflows developed for incident remediation are shared with Cat for approval before implementation.

6. **Communication and Reporting:**
   - Cat communicates incident details and remediation progress to Percy, providing updates on the situation.
   - Percy is personally informed if an incident is escalated, urgent, or remains unresolved after 48 hours.
   - Detailed incident reports are prepared and shared with Box Manufacturing for review and analysis.

7. **Post-Incident Review and Documentation:**
   - After the incident is resolved, Cat conducts a post-incident review to identify lessons learned and areas for improvement.
   - Documentation of the incident, response actions taken, and recommendations for future prevention are maintained for reference.
  
### Trigger Items:
- Time/date: Incidents detected during non-business hours may require immediate escalation to after-hours contacts.
- Incident severity: Incidents classified as critical or high trigger immediate notification to Cat and escalation to Misha or Minka.
- Unresolved incidents: Incidents remaining unresolved after 48 hours trigger personal notification to Percy.


### Sample Letter Template to the Client (Box Manufacturing)

```
Subject: Security Incident Notification

Dear Percy,

I hope this message finds you well. We wanted to inform you of a recent security incident detected within the Box Manufacturing network.

Description of Incident:
<A brief description of the incident, including severity level, impact, and current status would be included here.>

Actions Taken:
<Here we would outline the steps taken by the SOC and our team to investigate and remediate the incident.>

Next Steps:
<We would then include any further actions required and expected timelines for resolution.>

We will continue to keep you updated on the progress and appreciate your attention to this matter.

Best regards,
Jim Sher
SOC Analyst
jim@soc.dog
```

### Sample Letter Template to the Third-Party Provider (External MSSP & SOC)

```
Subject: Security Incident Response Collaboration

Dear Cat,

I hope this message finds you well. We would like to thank you for your swift response and assistance in addressing the recent security incident within the Box Manufacturing network.

Description of Incident:
<Provide a brief overview of the incident and actions taken thus far.>

Your expertise and collaboration have been invaluable in mitigating the impact of this incident. We appreciate your continued support in ensuring the security and resilience of our network.

Best regards,
Jim Sher
SOC Analyst
jim@soc.dog
```
