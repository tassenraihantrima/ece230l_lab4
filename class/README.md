# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

We learned how to use KMaps to minimize equations, and then we learned how to test and check the minimized equations using the test file and the board.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
Because the KMap wraps around, so the edges are connected to each other, kind of like a cylinder.

### Why are the names Sum of Products and Products of Sums?
For Sum of Products, we first AND the terms and then OR them together. For Product of Sums, we first OR the terms and then AND them together.

### Open the test.v file – how are we able to check that the signals match using XOR?

If the signals are the same, XOR gives an output of 0. If the signals are different, it gives an output of 1, so we can use that to check if they match.