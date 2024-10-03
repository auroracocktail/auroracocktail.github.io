---
title: Dijkstra Algorithm
author: R.D.W
date: 2024-10-02
category: [ Programming, "Data Structures", Graph ]
layout: post
mermaid: true
---

## what is a Dijkstra algorithm?

Dijkstra algorithm is an algorithm to *find the shortest paths* from one specific node to all other nodes in a graph. the weights of the graph must be *non-negative*.

```
graph TD
  A["A"] -- "4" --> B["B"]
  A -- "8" --> C["C"]
  B -- "2" --> D["D"]
  B -- "6" --> E["E"]
  C -- "7" --> F["F"]
  C -- "3" --> G["G"]
  D -- "1" --> H["H"]
  E -- "5" --> I["I"]
  F -- "9" --> J["J"]
  G -- "2" --> I
  H -- "3" --> J
```