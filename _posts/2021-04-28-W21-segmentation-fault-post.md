---
title: "W21: Segmentation fault"
last_modified_at: 2021-04-28
categories: [Blog]
tags: [winter,school]
toc: true
toc_sticky: true
excerpt: "Segmentation fault"
header:
  teaser: assets/images/w21-thumbnail.jpg
  overlay_image: assets/images/w21-header.jpg
  overlay_filter: 0.25
---

# Segmentation fault

```c
#include <stdio.h>

int main(int argc, char** argv)
{

  char* ptr = "Hello, World!\n";

  *ptr = 'A'

  return 0;

}
```

In the winter of 2021, my second semester at the Univeristy of Guelph began. We continued learning remotely with covid-19 still at its height. Feeling more comfortable and confident in my abilities as a student, I was eager to move forward and learn more about Computer Science. 

***

# CIS*2500 Intermediate Programming

In this course we continued our journey into the C programming language. We covered topics such as, I/O, pointers, dynamic memory allocation, the preprocessor, and bit manipulation. This course moved me closer to the machine and piqued my interest in low-level programming. All these new tools allowed me to create more complex programs and work on small personal projects.