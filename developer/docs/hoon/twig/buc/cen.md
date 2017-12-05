---
navhome: /developer/docs/
next: true
sort: 3
title: $% "buccen"
---

# `$% "buccen"` 

`[%bccn p=(list [[aura @] moss])]`: mold which recognizes a union tagged by head atom.

## Normalizes to

For any item `i` in `p`, a cell whose head is the atom `q.p.i.p`,
and whose tail recognizes `q.i.p`.

Void if `p` is empty.

## Defaults to

For the first item `i` in `p`, the cell `[q.p.i.p $:q.i.p]`.
Crashes if `p` is empty.

## Syntax 

Regular form: *2-running*.

## Discussion

A `$%` ("buccen") is a tagged union, an extremely common data model.

Make sure the first item in your `$%` terminates, or the default will 
be an infinite loop!

## Examples

```
~zod:dojo> =foo $%([%foo p=@ud q=@ud] [%bar p=@ud])

~zod:dojo> (foo [%bar 37])
[%bar p=37]

~zod:dojo> $:foo
[%foo p=0 q=0]~
```
