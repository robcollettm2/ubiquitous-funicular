### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| Id      | Guid |
| OwnerId      | Guid? |
| Name | string      |
| Vendor | string      |
| Posted | decimal      |
| MultipliedPosted | decimal      |
| Value | decimal      |
| PostedResourceCount | int     |
| Modified | datetime      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| AccountCode | Can be tag      |
| UnitOfMeasure | Can be tag      |
| ProposedVendor | Can be tag      |
| ResourceType | Can be tag      |
| TradeType | Can be tag      |
| ChangesSincePost | soft field |

(n.b. all removed fields can be set up as tags)
