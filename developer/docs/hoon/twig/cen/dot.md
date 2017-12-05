---
navhome: /developer/docs/
next: true
sort: 2
title: %. "cendot"
---

# `%. "cendot"` 

`{$cndt p/seed q/seed}`: call a gate (function), reversed.

## Expands to

```
%-(q p)
```

## Syntax

Regular: *2-fixed*.

## Examples

```
~zod:dojo> =add-triple |=({a/@ b/@ c/@} :(add a b c))
~zod:dojo> %.([1 2 3] add-triple)
6
```

