### Property Fields

| Field        | Type           | 
| ------------- |:-------------:|
| ProjectId      | Guid |
| ParentId      | Guid?      |
| Name | string      |
| Levels | int      |
| Nett | decimal      |
| Multiplied | decimal      |
| Gross | decimal      |
| Modified | datetime      |

### Removed Fields

| Field        | Reason           | 
| ------------- |:-------------:|
| ProjectGifaUnit      | To be made tag |
| Password      | Project only available to those shared and owner      |
| BuildingType | To be made tag      |
| ProjectType | Folder hierarchy to be stored in SQL - no longer need to use Project as Folder      |
| Isolate | See password      |
| ProjectGifa | To be made tag      |
| CostM2 | to be made soft field based on gifa      |
| CostDate | To be made tag       |
| Version | To be made tag       |
