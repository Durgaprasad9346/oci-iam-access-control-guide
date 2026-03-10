# Dynamic Groups and Instance Principals

Dynamic groups allow compute instances to access OCI services securely without storing API keys.

Instances are automatically included in dynamic groups based on rules.

---

## Example Dynamic Group Rule

ALL {instance.compartment.id = '<compartment_ocid>'}


---

## Access Flow


Compute Instance
│
▼
Dynamic Group
│
▼
IAM Policy
│
▼
Access OCI Services



---

## Example Policy

Allow dynamic-group app-instances to read buckets in compartment Storage



This policy allows instances to access Object Storage securely.

