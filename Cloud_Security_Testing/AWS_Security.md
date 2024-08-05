---
### 41. **Cloud_Security_Testing/AWS_Security.md**

```markdown
# AWS Security

## Overview
AWS Security involves protecting resources and data in Amazon Web Services. It includes securing compute instances, storage, and network configurations.

## Techniques
- **IAM Policies** - Defining and managing access permissions using AWS IAM (Identity and Access Management).
- **Security Groups** - Configuring firewalls to control inbound and outbound traffic to AWS resources.
- **Encryption** - Using encryption for data at rest and in transit.

## Example
Creating an IAM policy to restrict access:
```json
{
  "Version": "2012-10-17",
  "Statement": [
    {
      "Effect": "Allow",
      "Action": "s3:ListBucket",
      "Resource": "arn:aws:s3:::my-bucket"
    }
  ]
}

