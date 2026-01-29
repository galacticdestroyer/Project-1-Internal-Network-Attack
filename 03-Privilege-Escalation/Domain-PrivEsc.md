
## Domain Privilege Escalation

### Objective
Escalate privileges within the Active Directory domain environment.

### Enumeration Focus
- Group memberships
- Delegated permissions
- Service accounts
- Kerberos configurations
- Access control lists (ACLs)

### Potential Techniques
- Kerberoasting
- Abuse of weak service account passwords
- Privilege escalation via group membership misconfigurations
- ACL abuse

### Identified Weaknesses
- Excessive permissions assigned to non-admin accounts
- Service accounts with weak password policies
- Lack of monitoring on privileged group changes

### Security Impact
Domain privilege escalation leads to complete compromise of the Active Directory environment.
