
---

### 42. **Cloud_Security_Testing/Azure_Security.md**

```markdown
# Azure Security

## Overview
Azure Security involves safeguarding resources and data in Microsoft Azure. It includes securing virtual machines, databases, and network configurations.

## Techniques
- **Azure Active Directory** - Managing identities and access using Azure AD.
- **Network Security Groups** - Configuring firewalls to control traffic to Azure resources.
- **Azure Security Center** - Using Azure Security Center to monitor and protect resources.

## Example
Creating a network security group rule:
```json
{
  "name": "AllowSSH",
  "properties": {
    "protocol": "Tcp",
    "sourcePortRange": "*",
    "destinationPortRange": "22",
    "sourceAddressPrefix": "*",
    "destinationAddressPrefix": "*",
    "access": "Allow",
    "priority": 100,
    "direction": "Inbound"
  }
}

