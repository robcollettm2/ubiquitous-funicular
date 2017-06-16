## Project

> Currently a project can be created in the cloud and locally. Projects can be locally imported from many different sources. 

> A project can be uploaded to the cloud to merge (where exists) the local content with the cloud content. Where the project doesn't exist in the cloud the local copy matches the cloud copy and a new cloud copy is created. Subsequent local project changes can be merged to the cloud. Merging allows the system to allow the user to work on different nodes, enquiry types and trade packages.

> This merge process requires knowledge to understand (clumsy) the difference between the local copy and the cloud copy and the effects of the process. We do not allow the user to store notes of what they've done and why etc.

> The merge process is not automatic and so cloud backups etc. can not be maintained. Moving to another machine requires a cloud merge (i.e. computer failure would remove all non-synched data)

- The cloud/local project hierarchies should be combined to remove the complexities of which version of projects are where
- The process needs to be automated whereby changes the user makes are merged back to the cloud where possible (connectivity etc.)
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
