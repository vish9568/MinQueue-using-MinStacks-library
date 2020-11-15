# MinQueue-using-MinStacks-library
This is implementation of queue using two stacks. That provides the basic functionalities of a queue with the added functionality of getting the smallest element currently in the queue in amortized O(1) time…

The MinQueue uses two MinStacks to simulate the behaviour of a Queue. Functionalities :<br>

1.push(x) : push element x at the back of the queue<br>
2.pop : remove an element from the front of the queue.<br>
3.top : return the element currently at the front of the queue.<br>
4.getMin : return the current smallest element in the queue.<br>

How to use:<br>
1.first include the MinQueue.h file in the program as #include "MinQueue.h"<br>
MinQueue < int > Q: <br>
Q.push(22); <br>
Q.push(1); <br>
Q.push(10); <br>
// currently Q looks like 22 -> 1 -> 10 <br>
// Q.getMin() returns 1. <br>
