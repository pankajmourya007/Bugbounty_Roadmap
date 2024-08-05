
---

### 43. **Cloud_Security_Testing/GCP_Security.md**

```markdown
# GCP Security

## Overview
GCP Security involves protecting resources and data in Google Cloud Platform. It includes securing compute engines, storage, and network configurations.

## Techniques
- **IAM Roles** - Managing permissions and access using GCP IAM roles.
- **Firewall Rules** - Configuring rules to control network traffic to GCP resources.
- **Data Encryption** - Encrypting data at rest and in transit.

## Example
Creating an IAM role with specific permissions:
```json
{
  "role": "projects/my-project/roles/myCustomRole",
  "title": "My Custom Role",
  "permissions": [
    "storage.buckets.list",
    "storage.objects.get"
  ]
}

