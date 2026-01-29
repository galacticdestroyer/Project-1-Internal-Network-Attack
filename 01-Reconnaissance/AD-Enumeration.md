
## Active Directory Enumeration

### Objective
Gather information about the Active Directory environment to identify privilege escalation and lateral movement opportunities.

### Enumeration Focus
- Domain structure
- User accounts
- Group memberships
- Service accounts
- Trust relationships

### Observations
- Domain users possess excessive permissions in certain groups
- Service accounts present with potential misconfigurations
- Privileged groups are not tightly restricted

### Potential Attack Paths
- Abuse of weak service account permissions
- Kerberoasting opportunities
- Privilege escalation via group membership abuse

### Security Impact
Improper Active Directory hardening significantly increases the risk of domain compromise.
