---
navhome: /developer/docs/
next: true
sort: 1
title: ~& "sigpam"
---

# `~& "sigpam"`

`[%sgpm p=seed q=seed]`: debugging printf.

## Expands to

`q`.

## Convention

Prettyprints `p` on the console before computing `q`. 

## Syntax

Regular: *2-fixed*.

## Examples

```
~zod:dojo> ~&('halp' ~)
'halp'
~

~zod:dojo> ~&  'halp' 
           ~
'halp'
~
```
