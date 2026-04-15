# Number Theory: Addition

In this lab, you’ve learned about One Hot and Binary state machines and how to build them.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name

Madison Hickey & Austin Maples

## Summary

In this lab we implemented the same state machine using both one hot encoding and binary encoding. One hot uses one flip flop per state which makes it easier to understand and debug, while binary uses fewer flip flops but requires more complex logic. Both implementations behave the same even though they are structured differently.

## Lab Questions

### Compare and contrast One Hot and Binary encodings

One hot encoding uses one flip flop per state, and only one is active at a time. This makes the logic simpler and easier to read. Binary encoding represents states as binary numbers, which uses fewer flip flops but makes the logic more complicated. Both methods represent the same state machine but trade off simplicity and resource usage.

### Which method did your team find easier, and why?

One hot encoding was easier because each state directly corresponds to a flip flop, so it is easier to see what state the machine is in 
and follow transitions and led outputs are more straightforward.

### In what conditions would you have to use one over the other? Think about resource utilization on the FPGA.

One hot is better when simplicity and clarity are more important, especially for smaller designs. Binary is better when you need to save hardware resources, especially when the number of states increases and you want to minimize flip flop usage.
