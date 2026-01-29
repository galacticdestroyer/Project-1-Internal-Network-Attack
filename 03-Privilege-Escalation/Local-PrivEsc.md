
## Local Privilege Escalation

### Objective
Identify misconfigurations on compromised systems that allow elevation from a standard user to local administrator.

### Enumeration Focus
- Running services
- Scheduled tasks
- Installed applications
- Privileged file permissions
- Credential artifacts

### Observations
- Misconfigured services running with elevated privileges
- Weak permissions on service binaries
- Potential credential exposure in memory or configuration files

### Attack Opportunities
- Service binary replacement
- Abuse of scheduled tasks
- Credential harvesting for privilege escalation

### Security Impact
Local administrator access allows attackers to dump credentials, disable defenses, and prepare for lateral movement.
