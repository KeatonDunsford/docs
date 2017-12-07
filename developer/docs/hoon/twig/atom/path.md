---
navhome: /developer/docs/
sort: 4
title: Path
---

# Path

`[%path p=(list (each @ta seed))]`: path with interpolation.

### Produces

A null-terminated list if  of the items in `p`, which are either constant
`@ta` atoms (`knot`), or twigs producing a `knot`.

### Syntax

Irregular: `/foo/bar/baz`.

### Examples

```
~zod/dojo> /foo/bar/baz
/foo/bar/baz

~zod/dojo> `path`/foo/[`@ta`(cat 3 %moo %bar)]/baz
/foo/moobar/baz/

~zod:dojo> /
~
```
