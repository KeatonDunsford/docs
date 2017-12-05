---
navhome: /developer/docs/
next: true
sort: 5
title: %+ "cenlus"
---

# `%+ "cenlus"` 

`{$cnls p/seed q/seed r/seed}`: call with pair sample.

## Expands to

```
%-(p [q r])
```

## Syntax

Regular: *3-fixed*.

## Examples

```
~zod:dojo> =add-triple |=({a/@ b/@ c/@} :(add a b c))
~zod:dojo> %+(add-triple 1 [2 3])
6
```
