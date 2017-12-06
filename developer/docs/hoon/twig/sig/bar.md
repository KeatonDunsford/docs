---
navhome: /developer/docs/
next: true
sort: 4
title: ~| "sigbar"
---

# `~| "sigbar"`

`[%sgbr p=seed q=seed]`: tracing printf.

## Expands to

`q`.

## Convention

Prettyprints `p` in stack trace if `q` crashes.

## Syntax

Regular: *2-fixed*.

## Examples

```
~zod:dojo> ~|('sample error message' !!)
'sample error message'
ford: build failed

~zod:dojo> ~|  'sample error message' 
           !!
'sample error message'
ford: build failed
```
