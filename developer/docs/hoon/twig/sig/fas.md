---
navhome: /developer/docs/
next: true
sort: 9
title: ~/ "sigfas"
---

# `~/ "sigfas"`

`[%sgfs p=term q=seed]`: jet registration for gate with
registered context.

## Expands to

```
~%(p +7 ~ q)
```

## Syntax

Regular: *2-fixed*.

## Examples

From the kernel: 
```
++  add
  ~/  %add
  |=  [a=@ b=@]
  ^-  @
  ?:  =(0 a)  b
  $(a (dec a), b +(b))
```
