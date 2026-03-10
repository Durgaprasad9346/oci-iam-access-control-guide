# Advanced IAM Access Patterns

OCI IAM provides advanced authentication mechanisms for secure service access.

These include:

- Instance Principals
- Resource Principals
- Dynamic Groups
- Delegation policies

---

## Instance Principals

Instance principals allow compute instances to authenticate with OCI services using instance identity rather than API keys.

---

## Resource Principals

Resource principals allow OCI services such as Functions or OKE workloads to authenticate with OCI services.

---

## Example Architecture

Compute Instance
│
▼
Instance Principal
│
▼
Dynamic Group
│
▼
IAM Policy
│
▼
OCI Services


---

## Best Practices

- Avoid storing API keys on servers
- Use dynamic groups for compute access
- Follow least privilege access principles

- 
