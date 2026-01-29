
## Initial Access – Assumed Breach Scenario

### Assumption
The attacker is assumed to have obtained access to a low-privileged domain user account through unknown means (e.g., phishing, credential reuse, or malware).

### Access Level
- Standard domain user
- No local administrator privileges
- No direct access to Domain Controller

### Objectives
- Enumerate accessible systems
- Identify privilege escalation opportunities
- Prepare for lateral movement

### Initial Capabilities
- Domain authentication possible
- SMB, LDAP, and Kerberos services accessible
- Ability to execute commands within user context

### Security Impact
Even low-privileged access within an internal Active Directory environment can lead to full domain compromise if misconfigurations exist.
