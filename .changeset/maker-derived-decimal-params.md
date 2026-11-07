---
"@osdk/maker": patch
---

Carry a decimal property's precision and scale into action parameters derived from it, instead of emitting a decimal parameter without them. A property that sets only one of them passes the property's default for the other; a property that sets neither keeps an unbounded parameter.
