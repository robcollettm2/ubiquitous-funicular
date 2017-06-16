## Project

> Currently a project can be created in the cloud and locally. Projects can be locally imported from many different sources. 

- The cloud/local project hierarchies should be combined to remove the complexities of which version of projects are where
- As per the Business document the project structure/content is primarily stored in the cloud
  - A cached mirrored local version should be maintained by the software at all times
- The project hierarchy is different for every user and not maintained by a group
  - Owned/Shared projects can be stored in a user specific hierarchy wherever the user chooses
- A primary cloud-based hierarchy would allow use across more than one application/device
- A project can be 'owned' whereby the owner can choose who to share the project with
  - Email based sharing
- A project can be shared with one of many users and will appear as a shared project in the ui
  - a shared project can not be deleted, renamed by the 'sharee'
  - the locking rules currently still apply (i.e. node, trade, enquiry type)
