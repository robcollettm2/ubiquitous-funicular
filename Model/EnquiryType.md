### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| Id      | Guid |
| OwnerId      | Guid? |
| Name | string      |
| Vendor | string      |
| Posted | string      |
| MultipliedValue | decimal      |
| Value | decimal      |
| PostedResourceCount | int     |
| Modified | datetime      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| ProposedVendor | Can be tag      |
| ChangesSincePost | soft field |

(n.b. all removed fields can be set up as tags)
