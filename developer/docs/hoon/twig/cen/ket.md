---
navhome: /developer/docs/
next: true
sort: 4
title: %^ "cenket"
---

# `%^ "cenket"` 

`[%cnkt p=seed q=seed r=seed s=seed]`: call with triple sample.

## Expands to

```
%-(p [q r s])
```

## Syntax

Regular: *4-fixed*.

## Examples

```
~zod:dojo> =add-triple |=([a/@ b/@ c/@] :(add a b c))
~zod:dojo> %^(add-triple 1 2 3)
6
```
