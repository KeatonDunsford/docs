---
navhome: /developer/docs/
next: true
sort: 3
title: =~ "tissig"
---

# `=~ "tissig"` 

`[%tssg p=(list twig)]`: compose many twigs.

## Produces

The product of the chain composition. 

## Syntax

Regular: *running*.

## Examples

```
~zod:dojo> =foo =|  n=@ 
                =<  =~  increment
                        increment
                        increment
                        n
                    ==
                |%
                ++  increment
                  |-  
                  ..increment(n +(n))
                --
~zod:dojo> foo
3
```
