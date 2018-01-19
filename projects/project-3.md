---
layout: project
type: project
title: Simple Circuit Analyzer
permalink: projects/simple-circuit-analyzer
# All dates must be YYYY-MM-DD format!
date: 2017-11-20
labels:
  - C++
summary: A simple circuit analyzer made for EE 205.
---


In EE205, Object-Oriented Programming, Cristina, my partner, and I decided to make a program that would analyze a simple circuit.  This program would ask for inputs and allow the user to input up to 7 elements into 2 loops. The program had a few fail-safes to ensure that there would be no impossible setups (mainly conflicting current sources). Below is the struct that we used to hold the data for each element in the circuit.

<img class="ui image" src="{{ site.baseurl }}/images/struct.PNG">
