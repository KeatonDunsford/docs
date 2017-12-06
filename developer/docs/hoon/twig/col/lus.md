---
navhome: /developer/docs/
next: true
sort: 3
title: :+ "collus"
---

# `:+ "collus"`

`[%clls p=seed q=seed r=seed]`: construct a triple (3-tuple).

## Expands to:

```
:-(p :-(q r))
```

## Syntax

Regular: *3-fixed*.

## Examples

```
/~zod:dojo> :+  1
              2
            3
[1 2 3]
/~zod:dojo> :+(%a ~ 'b')
[%a ~ 'b']
```
