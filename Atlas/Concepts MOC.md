up:: [[Home]]
tags:: #map

# Concepts MOC

### Unrequited Notes
These notes point directly to this note. But this note doesn't point back.
This is the strongest contextual query. (Lists MoC pointing to concepts)

```dataview
LIST

FROM [[Concepts MOC]]
and outgoing([[Concepts MOC]])
and -#map
and !"Home"

SORT file.link asc
```

### Possibly Relevant, Currently Unmentioned Notes
These notes have the tag `#concept`, and are not mentioned above—but could be relevant.
This is a nicely fuzzy contextual query.

```dataview
LIST 

FROM #concept
AND !outgoing([[Concepts MOC]])
AND !"Extras/Templates"
SORT file.link asc
```

---

Back to: [[Home]]