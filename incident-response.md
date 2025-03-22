# Incident Response Plan for Phishing Scenerio

## Incident Overview
An employee reports a phishing email that looked like it was from our CEO. They clicked a link, entered their password, and realized hours later that it was a scam.

## Step-By-Step actions to investigate the incident

### Step 1: Immidiate Isolation

- **Isolate User Account**
Our first step should be identifying and resetting the compromised employee's account password for cutting off the access from the scammer.

- **Terminate Active Sessions:** 
Even though we isolated device from the scammer, there might be some of the session opened with the name of the respective employee so our next step should be identifying and closing all the active sessions (from both on-prem and cloud platform) of the identified employee .

- **Isolating Device:** As this point scammer might have already infected the employee device with malware so to prevent further damage we should isolate the device from the network as soon as possible.


### Step 2: Notification

####Internal Notifications:

We should clearly notify all internal personal who are responsible for incident management, investigation and mitigation. If we properly notify the internal personnel, we can promptly avoid confusion and delay of service during incident response time to perform coordinated action during the incident. The internal personals who we should notify should include:

• Incident Response Team 
• IT Department
• Human Resources (HR)
• Employee’s direct manager
• Legal department

#### External Notifications:
- Notifying CISA (for government-related incidents).
- Informing Third-party vendors or external security resources (if required for investigation).

### Investigation and Analysis

• **Email Analysis:** Properly checking domain of the email, email headers, content and embedded URLs for identifying phishing techniques of the scammer's email.
• **Account Logs Review:** Reviewing the accounts logs of compromised account for finding out suspicous login and attempts 
• **Network and System Logs:** Promptly Investigating the organization's network's and firewall (includig IPS/IDS) for tracing unauthorized activity.
• **Malware Analysis:** Examining the affected device for finding out the traces of malware

### Eradication and Recovery
• Restoring affected device to a known secure baseline.
• Restoring the affected employee’s account with (Multi factor Authetication) MFA mechanism.
• Properly Monitoring the affected employee accounts and devices for identifying abnormalities. 

### Post-Incident Activities
• Documenting everything that is done incident response period including every timeline, actions taken and as well as information gathered. 
• Conducting a blameless post-incident meeting with all the stakeholders to identify lessons learned and improvement areas to prevent from such incident.
• Updating incident response pan and cybersecurity training based on findings based on the  post-incident meeting for takling the similar situation in future.


## Long-Term Improvements





