### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| Id      | Guid |
| ForeignId      | Guid      |
| Times | string      |
| Dims | string      |
| Total | string      |
| Sequence | int      |
| Tags | int      |
| Use | bool      |
| Modified | datetime      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| Annotation | To use tags      |
| BottomDim | Calc. as required    |
| DimType | Calc. as required     |

(n.b. all removed fields can be set up as tags)
