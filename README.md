# QiskitFallFest21-AU  

# Why Random Numbers?  

Random number generation is one of the security elements in today's world (Increasing No. of application, Increasing No. of IoT devices) for safety and trusted communications.  Random number generators must be able to provide true randomness and the possibility of predictions should be minimized as much as possible.   

# Why Quantum Random Number Generators?  

(PRNGs: Pseudo-Random Number Generators) able to generate randomness but at the same time it is predictable. A cryptographic algorithm can be used to produce very high-quality pseudo-random number generators but at the same time, they are slower than other generators. Hardware Random Number generation depends on classical physics processes which are sometimes uncontrollable.  

The very nature of quantum mechanics is probabilistic and randomness lies at the heart of it. Quantum computation therefore can be the perfect tool to create actually-random numbers with low memory and time cost. Quantum RNGs are able to produce true randomness, exploiting elementary quantum optic processes.   

# Our Idea  

While a very basic random number generator can be created using quantum computaion, it turns out it has some serious limitations. So we propose a variational quantum RNG, where we have tried to use a varying parameter to generate a list of unique random numbers.