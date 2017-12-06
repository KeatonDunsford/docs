---
navhome: /developer/docs/
next: true
sort: 2
title: ^+ "ketlus"
---

# `^+ "ketlus"`

`[%ktls p=seed q=seed]`: typecast by example (seed).

## Produces

The value of `q` with the span of `p`, if the span of `q` nests
within the span of `p`.  Otherwise, `nest-fail`.

## Syntax

Regular: *2-fixed*.

## Examples

```
~zod:dojo> ^+('text' %a)
'a'
```
