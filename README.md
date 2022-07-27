# Tolerant-Max-Cut

This repo includes the project I worked on for the CS498: Semester Project course at EPFL during Spring 2022 semester.

We present a sublinear-time algorithm for testing whether a bounded degree expander graph has a max-cut value close to 1 or far from 1. Graphs are represented by incidence lists of bounded length d, and the testing algorithm can perform queries of the form: “who is the i-th neighbor of vertex v”. The tester should determine with high probability whether the max-cut value is greater than 1 − ϵ1 or less than 1 − ϵ2. Our testing algorithm has query complexity and running time O(√n log2 n/ϵ1) where n is the number of graph vertices and ϵ1 is the tolerance value.
