## Business

>A business is currently used for the following purposes:

* Storing business-related lists which are pushed down to a user at a given point such as resource types, trade packages etc.
* Grouping projects under the umbrella of a business (and region) and project must be 'owned' by a single business and thus can't be shared cross business/region.
* Tieing a user to a given business to constrain which projects a user can see and which lists a user can use
* Creating a semblance of reporting consistency across a business

>This creates inflexibility where a user needs to work across more than one business/region. Consistency tends to be lost as users modify the lists as the list content is used within a project. A user is able to see every project another business/region group user has created and can edit it.

* Remove the concept of businesses and regions
* The user becomes an 'owner' of a project
* Each project can be shared with email addresses (or not)
  - Each shared user can be a read only/read-write user
* Each user has their own folder structure hosted in the cloud. Shared projects can be moved in to the location of their choice on their hosted structure
* As each user has their own structure it will be easier to manage and caching made easier
* Later on we could have the backend mechanism of grouping users based on email and thus projects (for reporting and such like)

#### Groups

>A user could belong to one or many Groups. A group is simply a list of Users. It's up for debate who the curators of groups could be as groups don't 'belong' to anyone (unless a user)
