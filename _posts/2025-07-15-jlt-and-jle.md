---
layout: post
title: JLT and JLE
---

Here is an interesting question.   
Why BPF JLT and JLE instructions   
were not introduced in the beginning?

Classic BPF did not have them   
and BPF authors felt compiler   
workaround would be acceptable.

Turned out that programs   
lose performance due to lack   
of these compare instructions.

These two instructions is a   
perfect example what kind of new   
BPF instructions are acceptable   
and can be added in the future.
