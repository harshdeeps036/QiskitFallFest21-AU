# QiskitFallFest21-AU   

This is a project submitted for the Allahabad University campaign at Qiskit Fall Fest 2021. The team consists of:  

* Harshdeep Singh  
* Abhi Patel  
* Paridhi Jain  
* Purvan Sheth

# Why Random Numbers?  

Random number generation is one of the security elements in today's world (Increasing No. of application, Increasing No. of IoT devices) for safety and trusted communications.  Random number generators must be able to provide true randomness and the possibility of predictions should be minimized as much as possible.   

# Why Quantum Random Number Generators?  

PRNGs (Pseudo-Random Number Generators) are able to generate random numbers but only to some extent, as there can be dependencies and patterns found within. A cryptographic algorithm can be used to produce very high-quality pseudo-random number generators but at the same time, they are slower than the other generators, and time becomes a huge factor for industry-level applications. Hardware Random Number generation depends on classical physics processes which are sometimes uncontrollable.  

The very nature of quantum mechanics is probabilistic and randomness lies at the heart of it. Quantum computation therefore can be the perfect tool to create actually-random numbers with low memory and time cost. Quantum RNGs are able to produce true randomness, exploiting elementary quantum optic processes.   

# Our Idea  

While a very basic random number generator can be created using a simple quantum circuit, it turns out it has some serious limitations, like the very limited number of unique random numbers generated, and the qubits requirement. So we propose a variational quantum RNG, where we have tried to use a varying parameter to generate a list of unique random numbers. We found that with the variational RNG, we were able to generate a list of unique random numbers, and with a lower qubit requirement, executing the circuit with only two qubits.
