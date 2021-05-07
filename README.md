# Distributed-Process-Mining

As part of my Masters research project, I devised a novel algorithm that can securely construct process models from distributed (geographically dispersed) process logs. Such an algorithm has a number of real world applications. It can for example be used to analyze and obtain meaningful insights from process logs generated by the IT systems deployed inside health-care organizations.


View Paper: https://github.com/asjad99/Distributed-Process-Mining/blob/main/Distributed_Process_Mining.pdf 


#### Experiment: 

In the previous section, through formal methods we established that the quality of model(precision, generalization etc.)  generated will be exactly the same as with the original  FHM. This is because the logical steps to generate dependency graph and XOR/AND splits in Phase 1 and 2 are exactly the same as proposed by the original FHM.   Focus of this section is on analyzing the performance and scalability of the proposed distributed process mining algorithm. Firstly using the PLG process log generator [10], we generate an event logs of various task lengths. Next we assume a ring topology and for various network configurations, we record the bit complexity and total execution time(shown in table 1).   

*ADD CODE*
