## Vendors

We currently store a lot of project vendor properties which aren't used moving forward. The user tends to use the name of the vendor and it's email only.

* Remove address detail from vendors (see model spec.) and provide functionality to allow the user to lookup the address details from the cloud based on vendor name and email
* The user could be presented with a list of possible vendors (should more than one share the same name and email)
  - We need to keep an address bookup available via lookup in the cloud  
* Library of vendors:
  - In the cloud one big list with address detail etc.
  - Cloud lists (which a user can save as a set of vendors) of vendors that a user can choose to use which are cached locally (names and emails only with matching tags)
