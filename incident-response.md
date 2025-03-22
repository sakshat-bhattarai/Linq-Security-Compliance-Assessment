# Incident Response Plan for Phishing Scenario

## Incident Overview
An employee reports a phishing email that looked like it was from our CEO. They clicked a link, entered their password, and realized hours later that it was a scam.

## Step-by-Step Actions to Investigate the Incident

### Step 1: Immediate Isolation

- **Isolate User Account:**  
Our first step should be identifying and resetting the compromised employee's account password to cut off access from the scammer.

- **Terminate Active Sessions:**  
Even though we've isolated the device from the scammer, there might be active sessions open under the respective employee's account. Our next step is identifying and closing all active sessions (both on-premises and cloud platforms) associated with the employee.

- **Isolate Device:**  
At this point, the scammer might have already infected the employee's device with malware. To prevent further damage, we should isolate the device from the network as soon as possible.

### Step 2: Notification

#### Internal Notifications:

We should clearly notify all internal personnel responsible for incident management, investigation, and mitigation. Properly notifying internal personnel can promptly avoid confusion and service delays, ensuring coordinated action during incident response. The internal personnel to notify should include:

- **Incident Response Team**
- **IT Department**
- **Human Resources (HR)**
- **Employee’s Direct Manager**
- **Legal Department**

#### External Notifications:
- **Notifying CISA (for government-related incidents)**
- **Informing third-party vendors or external security resources (if required for investigation)**

### Investigation and Analysis

- **Email Analysis:** Properly checking the email domain, email headers, content, and embedded URLs to identify phishing techniques used by the scammer.
- **Account Logs Review:** Reviewing the account logs of the compromised account to find suspicious login attempts.
- **Network and System Logs:** Promptly investigating the organization's network and firewall logs (including IPS/IDS) to trace unauthorized activities.
- **Malware Analysis:** Examining the affected device to find traces of malware.

### Eradication and Recovery

- Restoring the affected device to a known secure baseline.
- Restoring the affected employee’s account with Multi-factor Authentication (MFA).
- Properly monitoring the affected employee’s accounts and devices for identifying abnormalities.

### Post-Incident Activities

- Documenting everything done during the incident response, including timelines, actions taken, and gathered information.
- Conducting a blameless post-incident meeting with all stakeholders to identify lessons learned and improvement areas to prevent future incidents.
- Updating the incident response plan and cybersecurity training based on findings from the post-incident meeting to handle similar future situations.

## Long-Term Improvements

### Security Awareness Training

- Conducting interactive phishing-awareness training and simulations to check their effectiveness.
- Educating employees on best practices for creating, managing, and protecting strong passwords through interactive sessions.
- Educating employees on reporting any suspicious activity or security incidents.
- Conducting semiannual cybersecurity workshops and quizzes to stay updated on various threat vectors and delivery methods.

### Technical Enhancements
- Enforcing Multi-factor Authentication (MFA) across all critical accounts and services.
- Deploying real-time URL scanning and email filtering solutions to detect and block suspicious emails.

### Policy and Procedural Updates
- Reviewing and updating incident response plans quarterly.
- Clearly documenting and reporting procedures for suspicious emails and other cybersecurity incidents.
- Defining clear roles and responsibilities for handling and escalating incidents within a properly established incident response team.
