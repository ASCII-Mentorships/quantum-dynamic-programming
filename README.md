# Quantum Dynamic Programming

### Goal
To implement algorithms that demonstrate a quantum speedup on dynamic-programming solutions to certain problems.


### Description
<img src="https://github.com/ASCII-Mentorships/quantum-dynamic-programming/blob/main/Hypercubestar.png" align="right" width="200"/>

The problems that will be taken up are - 
1. Path in the hypercube
2. Vertex ordering problems
3. Graph bandwidth
4. Travelling salesman problem
5. Feedback arc set
6. Minimum set cover

The quantum algorithms will precompute solutions for a part of the subsets using DP, and then use Grover's search on the remaining subsets to find the solution to the problem. 

### Background
Quantum computing is a fairly new and rapidly developing paradigm that harnesses the 'weirdness' of quantum particles to perform computational tasks efficiently. As computer scientists designing these algorithms, we do not need to know _why_ or _how_ the weirdness happens - we just need to know _what_ it is, and think of ways to use it advantageously. 

Dynamic programming is a technique used in computer science to solve a certain class of problems that require computing the solutions of subproblems to solve the bigger optimization problem. There are many [NP-complete](https://en.wikipedia.org/wiki/NP-completeness) problems that have dynamic programming solutions which take exponential time. The paper we are implementing in this project uses quantum computing to gain a speedup on these classical DP solutions - the results are still exponential time, but with a better complexity (Eg. $O(1.5^{n})$ is better than $O(2^n)$, even though both are exponential complexities).

### Plan of Action
- Week 1 - A few introductory exercises in quantum computing - learn Python, and what qubits and quantum gates are
- Week 2 - Basic quantum algorithms
- Week 3-6 - Implement the paper - each person can pick a problem and algorithm
- Week 7 - Final presentations


### Prerequisites and Techstack
- Some programming experience, preferably in Python - but you can learn on the way too
- The QC framework we will use is [Qiskit](https://qiskit.org/)
- Participants can also pick a different framework of their choice - [here is a list](https://github.com/qosf/awesome-quantum-software#quantum-full-stack-libraries)
- Note that a knowledge of quantum mechanics is NOT required

### Expectations and Deliverables 
- Clean, readable code
- A working Jupyter notebook with an implementation of the selected algorithm and an analysis and explanation of the problem, solution, and speedup
- Enthusiasm!

### Mentor
[Ayushi Dubal](https://ayushidubal.github.io/)


### References
https://arxiv.org/abs/1807.05209
