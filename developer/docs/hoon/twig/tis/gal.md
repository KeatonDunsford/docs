---
navhome: /developer/docs/
next: true
sort: 2
title: =< "tisgal"
---

# `=< "tisgal"`

`[%tsgl p=seed q=seed]`: compose two twigs, inverted.

## Expands to

```
=>(q p)
```

## Syntax

Regular: *2-fixed*.

Irregular: `foo:bar` is `=<(foo bar)`.

## Examples

```
~zod:dojo> =<(b [a=1 b=2 c=3])
2

~zod:dojo> =<  b 
           [a=1 b=2 c=3]
2

~zod:dojo> b:[a=1 b=2 c=3]
2

~zod:dojo> [. .]:(add 2 4)
[6 6]
```
