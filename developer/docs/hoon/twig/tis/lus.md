---
navhome: /developer/docs/
next: true
sort: 4
title: =+ "tislus"
---

# `=+ "tislus"`

`[%tsls p=seed q=seed]`: combine a new noun with the subject.

## Expands to

```
=>([p .] q)
```

## Syntax

Regular: *2-fixed*.

## Discussion

`:pin` is the simplest way of "declaring a variable."

## Examples
 
```
~zod:dojo> =foo  |=  a=@
                 =+  b=1
                 =+  c=2
                 :(add a b c)
~zod:dojo> (foo 5)
8
```
