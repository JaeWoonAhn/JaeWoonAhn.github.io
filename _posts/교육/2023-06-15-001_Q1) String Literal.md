---
layout: post
title:  "C_001 In C, Which part of program memory allocated 'String literal'??"
---

# Data Segment!!
## same with static variables!


The data segment contains initialized static variables, i.e. global variables and local static variables which have a defined value and can be modified. Examples in C include:

int i = 3;
char a[] = "Hello World";
static int b = 2023;    // Initialized static global variable
void foo (void) {
  static int c = 2023; // Initialized static local variable
}


https://en.wikipedia.org/wiki/Data_segment