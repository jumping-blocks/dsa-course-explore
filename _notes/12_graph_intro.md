---
layout: post
title:  "Intro to Graphs"
---

# Introduction to Graph Theory


## Graph and Tree Problems 

### Outdoor Navigation

Navigation around cities is a common graph problem. 



![alt text](https://jumping-blocks.github.io/dsa-course-explore/_images/notes/graphs/Maps_and_navigation.pdf "Map of LA showing nodes and paths")


{% include image.html url="/_images/notes/graphs/Maps_and_navigation.pdf" align="right" %}


![alt text](https://jumping-blocks.github.io/dsa-course-explore/_images/notes/graphs/Spatial_navigation.png "Map of inside space to navigate")


![alt text](_images/notes/graphs/Spatial_navigation.png "Map of inside space to navigate, relative URL")

{% include image.html url="/_images/notes/graphs/Spatial_navigation.png" align="right" width="200" %}




## What is a Graph? 

A graph $G$ is a pair $G = (V, E)$ where $V$ is a set of ***vertices*** or ***nodes***, and $E$ is a set of ***edges*** that connect the nodes/vertices. 

In other words, a graph is a collection of nodes and edges. Linked lists and trees are all special cases of graphs! 

### An Example


Here is a graph $$G = (V, E)$$. 

Here is a graph $G = (V, E)$. 

* Each edge is a pair $(v_1, v_2)$, where $v_1, v_2 \in V$. 
   * $V = \{ A, B, C, D, E, F \}$
   * $$V = \{ A, B, C, D, E, F \}$$ 
   * $E = \{ (A, B), (A, D) \}$


### Terminology: Undirected Graph

* Two vertices $u$ and $v$ are ***adjacent*** in an undirected graph $G$ if $\{u, v\}$ is an edge in $G$. 
