## What are the problem areas?

- Philosophy of software has changed and gone backward
    - Task based / single function
- Many ways to do one thing
- Must move around screens to do simple task
- Local > Cloud is clumsy
- Too many sets of data
    - (Tags with classifications? (i.e. trade, enquirytype, other))
- Too much ui
    - too bespoke
    - hard to discover functionality
- Difficult to start (relativly)
    - link to site
    - require a login
    - require .net 4.6.2
- No online presence
- Consolidation of functionality/screens required
- Project / Business data is overly complicated
    - we carry data where we don't need to
        - vendor 'classifications' (i.e. areas, enquiry types, trade etc.)
- Current cloud object structure is a very rigid structure
- Reports are either static pieces of paper of excel moving documents 
        
## How do we change the problems?

- The software should model itself on Excel - single screen, single function modern application
- Rationalise and remove functionality implemented in more than one way
- Single non-tiled screen
- Remove the difference between cloud and Local
    - One single list that caches locally where possible
    - Cloud syncs are done automatically
    - Remove complexity
- Remove different sets of name/value object sets (in most cases association/searching is done via name only)
- Return to standardised ui using system components to remove maintainence of user controls such as tools, menu bars, drop downs etc.
- Windows 10 UWP Store application targetting the widest range of OS's possible
    - Single simple low payment and manage user through the store
    - From store acquisition to use all managed through the software
    - No expiry date
- Simple website page explaining what the product is and it's functionality (link in store)
- Note very function and replicate where it makes sense
    - Hide those seldom functions away and bring the often used functions to the front of the ui
    - Simplify
- Data structures should be reviewed and removed where possible
- A user can belong to a hierarchy of 'things' - so no business/region etc.
- More work to do regarding moving tabular data to the cloud
