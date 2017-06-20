### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| Id      | Guid |
| ResourceType | string      |
| EnquiryType | string      |
| Description | string      |
| Unit | string      |
| NettQty | string      |
| Output | string      |
| Waste | string      |
| GrossQty | string      |
| NettRate | string      |
| NettTotal | calculated-string      |
| BaseRate | string      |
| Calc | string      |
| Sequence | int      |
| Level | int      |
| Tags | int      |
| Modified | datetime      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| ActivityCode | Can be tag      |
| Currency | Removed      |
| CostCode | See activity code     |

(n.b. all removed fields can be set up as tags)
