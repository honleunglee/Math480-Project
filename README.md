Math480-Project
===============

Hao Chen, Xin Guo, Hon Leung Lee, Di Wu

Topic 1:
Investigate this challenge problem: given a binary integer a, define an operation to be: add a any number of + signs between any two digits of a, and compute the sum. It's clear given any number, finitely many operations will change this number a to 1. Now the question is: How many operations do you need at most? An example: a = 100111011 -> 100+1+1+10+11 = 1011 -> 10+1+1 = 100 -> 1+0+0 = 1 Goal: give an absolute constant C, such that for any number a, there exists a sequence of at most C operations, changing a to 1.

Topic 2: 
Find out the best algorithm to solve the famous Fermat-Torricelli problem with weights. We shall investigate three methods to solve them.For details and papers about this topic see: 

https://drive.google.com/folderview?id=0B-LLRo89XGyvVWhhQnROTTVJWlU&usp=sharing

Further investigations: 
(1) Speed up all the algorithms involved.
(2) How to generalize the SDP method into d dimensions instead of d = 2? 
(3) If all the weights equal 1, the SDP problem looks "symmetric", in the sense that permutation of some variables unchanges the problem, can we do something based on this?
(4) It seems the matrices involved in the SDP formulation are sparse. Anything we can do concerning this point?
(5) Is it possible to geometrically construct Fermat-Torricelli point (together with reading the minimizer) in Sage? 
(6) Assume all the weights equal 1, we know Euclidean norm is not quite robust, what about changing Euclidean norm into a more robust norm like l_1 norm?

