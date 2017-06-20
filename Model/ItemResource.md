### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| Id      | Guid |
| ProjectItemId      | Guid      |
| ResourceType | string      |
| Trade | string      |
| EnquiryType | string      |
| Description | string      |
| Unit | string      |
| NettQty | string      |
| Output | string      |
| Waste | string      |
| GrossQty | string      |
| Calc | string      |
| BaseRate | string      |
| Adj1 | string      |
| Adj2 | string      |
| NettRate | string      |
| GrossRate | string      |
| GrossTotal | string     |
| Sequence | int      |
| Level | int      |
| Tags | int      |
| Use | bool      |
| Vendor | string      |
| VendorStamped | string      |
| Modified | datetime      |
| NettTotal | calculated-string      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| ActivityCode | Can be tag      |
| Currency | Single currency per project (project tag) (for reporting purposes only)      |
| CostCode | See activity code     |

(n.b. all removed fields can be set up as tags)
