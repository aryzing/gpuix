---
"@gpuix/native": patch
---

Show a pointing-hand cursor over links in `<markdown>`. The pointer changes only
on link text, because the cursor comes from a hitbox per painted link rect
rather than from the whole text run. Clicking still fires `onLinkClick` with the
URL.
