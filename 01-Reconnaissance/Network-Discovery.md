
## Network Discovery

### Objective
Identify live hosts, network ranges, and critical systems within the internal network.

### Assumptions
- Attacker has internal network access
- No prior knowledge of the network layout

### Methodology
The reconnaissance phase focused on identifying:
- Active hosts
- Domain Controller presence
- Network segmentation
- Potential high-value targets

### Findings
- Multiple Windows hosts detected within the internal subnet
- Presence of an Active Directory Domain Controller
- SMB and LDAP services exposed internally
- No network-level segmentation observed between user machines and servers

### Security Impact
Lack of internal segmentation allows attackers to move laterally once initial access is obtained.
