up:: [[Home]]
tags:: #map/view 

# Inbox
``` dataview
TABLE WITHOUT ID
 file.link as "Encounters and new notes",
 (date(today) - file.cday).day as "Days alive"

FROM "+ Encounters" and -#on/readme 

SORT file.cday asc

LIMIT 20
```
---