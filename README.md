# QiskitFallFest21-AU   

This is a project submitted for the Ahmedabad University campaign at Qiskit Fall Fest 2021. The team consists of:  

* Harshdeep Singh  
* Abhi Patel  
* Paridhi Jain  
* Purvam Sheth

# Why Random Numbers?  

Random number generation plays a lot of important roles in various areas like computational physics and chemistry say in Monte-Carlo simulations, arts, gaming, gambling etc. and is one of the very important security elements in today's world (with increasing no. of online applications, and IoT devices) for safety and trusted communications and with onset of quantum encryption, we need very good random number generators.  Random number generators must be able to provide true randomness and the possibility of predictions should be minimized as much as possible.   

# Why Quantum Random Number Generators?  

PRNGs (Pseudo-Random Number Generators) are able to generate random numbers but only to some extent, as there can be dependencies and patterns found within. A cryptographic algorithm can be used to produce very high-quality pseudo-random number generators but at the same time, they are slower than the other generators, and time becomes a huge factor for industry-level applications. Hardware Random Number generation depends on classical physics processes which are sometimes uncontrollable.  

The very nature of quantum mechanics is probabilistic and randomness lies at the heart of it. Quantum computation therefore can be the perfect tool to create actually-random numbers with low memory and time cost. Quantum RNGs are able to produce true randomness, exploiting elementary quantum optic processes.   

# Our Idea  

While a very basic random number generator can be created using a simple quantum circuit, it turns out it has some serious limitations, like the very limited number of unique random numbers generated, and the qubits requirement. So we propose a variational quantum RNG, where we have tried to use a varying parameter to generate a list of unique random numbers. We found that with the variational RNG, we were able to generate a list of unique random numbers, and with a lower qubit requirement, executing the circuit with only two qubits.  

# Link to Presentation:   
(Please use headphones)  

https://drive.google.com/file/d/14US7Fb4Ffnm8Gm7FZA_o_uoht0s-m9gH/view?usp=sharing
