# Grover-s-Algorithm
Grover's Algorithm
Finding an object/string of interest from a large pile of unstructured objects is what we know as a
search.Using a quantum Algorithm for this search is what we call a ’Quantum Search’.Classically to
find a string or an object of interest from large pile of objects it takes on an average N/2 queries to
oracle whereas Grover’s Algorithm does it in O√
N queries to the oracle.Grover Algorithm uses the
principle of Quantum Mechanics mainly ’Entanglement’ and ’Superposition’ and exploits the fact
that probability of measurement is square of the amplitude which is the main factor responsible for
quadratic speedup compared to classical available algorithms.
In this report I will give a detailed theoretical explanation of Grover’s Algorithm and its implementation for 3 Qubits on IBM Quantum Simulator as well as IBM Quantum Computer using a
database oracle which will again use 3 Qubits to encode the given classical data,followed by a brief
discussion on the results observed.
