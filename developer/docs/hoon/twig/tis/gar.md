---
navhome: /developer/docs/
next: true
sort: 1
title: => "tisgar"
---

# `=> "tisgar"` 

`[%tsgr p=seed q=seed]`: compose two twigs.

## Produces

`q`, compiled against the product of `p`.

## Syntax

Regular: *2-fixed*.

## Examples

```
~zod:dojo> =>([a=1 b=2 c=3] b)
2
~zod:dojo> =>((add 2 4) [. .])
[6 6]
```
