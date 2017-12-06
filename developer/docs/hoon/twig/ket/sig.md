---
navhome: /developer/docs/
next: true
sort: 4
title: ^~ "ketsig"
---

# `^~ "ketsig"`

`[%ktsg p=seed]`: fold constant at compile time.

## Produces

`p`, folded as a constant if possible.

## Syntax

Regular: *1-fixed*.

## Examples

```
~zod:dojo> (make '|-(42)')
[%8 p=[%1 p=[1 42]] q=[%9 p=2 q=[%0 p=1]]]
~zod:dojo> (make '^~(|-(42))')
[%1 p=42]
```

