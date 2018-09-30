---
title: "Dangling Pointer and Garbage"
date: 2018-09-30 21:49:28 +0900
categories: Memory
---

| | Access Path | Data Object
|-|--|--|
|Dangling Pointer| O | X
| Garbage| X | O

 The dangling pointer freezes what you should not free, which can cause serious errors. 
 On the other hand, Garbage wastes memory space because it does not do what it has to free.
