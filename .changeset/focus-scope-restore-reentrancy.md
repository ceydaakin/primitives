---
'@radix-ui/react-focus-scope': patch
'radix-ui': patch
---

Fixed a trapped `FocusScope` overflowing the call stack when an element outside it moves focus back to itself on `blur`.
