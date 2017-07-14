## Directory Structure

(.bbc files are minimal-spaced json files)

- Metre2
  - BlueBook
    - UserId1 (each hierarchy is per user)
      - Projects
        - Live (live project blobs)
        - Trash (deleted project blobs)
        * Projects.bbc (live project list json)
        * Recent.bbc (recent projectlist json
        * Trash.bbc (deleted project list json)
      - ResourceLibraries
        - Live (live library blobs)
        - Libraries.bbc (live library list json)
      - Cache
        - Columns
          * Window-GridName.bbc (window/grid specific column properties)
        - Favourites
          - VendorTrades
            * Trade1Id.bbc (specific tradeid containing max10 business vendor object json)
            * Trade2Id.bbc (")
          - VendorMaterials
            * Material1Id.bbc (specific enquirytypeid containing max10 business vendor object json)
        - Url
          - httpwww.metre2.co.uk (blob of specific url information)
          - httpwww.microsoft.com
        - Business
          - Region.bbc (user specific region object)
          - Business.bbc (user specific business object)
          - BusinessUser.bbc (user object)
          - BusinessDashboardProfile.bbc (user specific dashboard (formerly publisher) profile)
          - BusinessApplicationProfile.bbc (user specific bluebook profile)
          
