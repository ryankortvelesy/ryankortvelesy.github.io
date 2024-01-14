---
title: Symbolic Regression
date: '2024-01-13'
summary: Recovering analytical functions from data
---

How did Galileo discover that objects fall with constant acceleration? In the late 1500s, Galileo set out to disprove Aristotle's theory that objects fall at a constant rate---a somewhat concerning view from one who fathered the modern scientific method, and had presumably seen things fall before. To do so, he dropped two balls off of the leaning tower of Pisa--perhaps the world's most well-respected drop test venue--as anyone with a personal investment in gravitational physics looked on eagerly. Collecting one datapoint (i.e. the duration of the fall), he concluded that he was in fact correct, and gravity is characterised by a constant 
"aggiunta di velocità", which presumably means "acceleration" in Italian. Had he collected more datapoints and used this python package that I just developed, he might have more accurately concluded that acceleration is given by {{< math >}}$\frac{dv}{dt} = g - \frac{bv}{m}${{< /math >}}, taking air resistance into account.

This problem, involving taking a set of datapoints and converting it into a symbolic equation, is known as symbolic regression. It is famously difficult problem, as there is no known method of enumerating all possible analytical functions, much less a way to search through that space.