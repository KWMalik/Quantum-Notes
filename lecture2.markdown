Principles of Quantum Computing 
===============================

- Quantization: certain quantities are oly allowed to take on a discrete set of values. 
- Basic chem (Energy of an electron in a atom); 
nucleus -> ground state -> first excited state -> second excited state
- Quantization occurs when the particle is confined. 

Superposition Axiom 
---
- Suppose we have a k-level quantum system 
> k distinguishable or classicle states for the system 
> Possible classical states |0>, |1>,.....|k-1>. 
- Superposition principle: if a system can be in one of k states, it can also be in any linear superposition of those k states. 
- Superposition can be described as: 

a = (alpha) amplitude probability a0 = a sub zero
ai E C == "probability amplitude"

> a0|0> + a1|1> + ... + ak|k-1> 
- The sum of the <i>squares</i> of these amplitudes is always 1. 
- (for k-1 sigma(ai)^2 where i=0) == 1

> if k = 3 
> 1/sqrt(3)|0> + 1/sqrt(3)|1> + 1/sqrt(3)|2> 
- Normalized since the sum of the squares = 3 (COOL!) 
- These are arbitrary <b>complex</b> numbers
- i can also = sqrt(-1) 
- this means that you can have
> 1/2|0> - 1/2|1> + (1/2 + i/2)|2> 

Measurement axiom 
---
- When you measure an electron you don't see it in a superposition
- It makes up it's mind about what classical state it's in
- Suppose that our system is in stat
- Measure: outcome is one of the k classical states
> |V> = a0|0> + a1|1> + ... + aK|k-1>
- Measure: outcome is one of the k classical states
- - j with probability |aj| ^ 2
- - New state = |j> 
- 1/2|0> - 1/2|1>  + (1/2 + i/2)|2> 
Yields: 
0   1/4     |0> 
1   1/4     |1> 
2   1/2     |2>

Qubit
--- 
- special case of k level system
- two-level systems are called <b>qubits</b> (k=2)
- The electron can either be in the ground state or first excited state 
- represented by 1/2|0> + (1/2 + i/2)|1> 

Quantum Mechanis and Quantum Computation
========================================

- If we have a k-level system, that observed will go into a classical state: 
- Suppose a0|0> + a1|1> .... + aK|k-1> 
> This is eqivalent to (a0 a1 a2 ... ak)  **this is normally denoted as a stack.** 
- These are equivalent was of representing a system. 
- if k = 3, we'd be respresenting it in a 3 dimensional space. 
- Our state (represented as a stack) could be a unit vector. 

- The X axis represents ( 1 0 0 ) = |0, or in other words ground state 
- The Y axis represents ( 0 1 0 ) = |1, which is excited state 1. 
- The Z axis represents ( 0 0 1 ) = |2, which is excited state 2. 
- The funny way this is denoted is called Dirac notation. 

- A qubit could be described as a two dimensional space, with 2 possible states. 
> |Y> = a0|0> + a1|1> 
- If you make a measurement, 
- the probability that the outcome is 0
> Pr[0] = |a0|^2 = cos^2(theta) 
> Pr[1] = a1 ^ 2 = sin^2(theta)

Review and Computation 
======================

- If we have vector ut perpendicular to u
- and the probability described as theta prime
> u with probability cos^2(theta)           |u> 
> u^t (perpendicular) with prob sin^2(theta)|u^t> 


- For qubits, there is a particularly important basis called "sign basis."
> |+> = 1/sqrt(2)|0> + 1/sqrt(2)|1>
> |-> = 1/sqrt(2)|0> - 1/sqrt(2)|1>

- Can we distinguish from |+> from |->? 
- - Yes by measure in |+>/|-> basis: 
