# stochastic-project
Stochastic Processes Markov chain research project

This code has been written in order to analyze the absorbing Markov chain used in Liang et al. (2011). The outputs model first 
the chain without a constant input of carbon, showing that all carbon in the system eventually moves to the absorbing 
atmospheric state. The second output is a graphical representation of the chain with a constant input of carbon to living 
microbial biomass, indicating the steady states that are reached in the living microbial biomass and microbial necromass states, as the atmospheric state continues to increase in size over time. 
The transition probabilities were taken from Liang et al. (2011), they obtained the probabilities from various literature 
sources on microbial soil organic carbon movement.

The second part of the code calculates the fundamental matrix of the absorbing Markov chain and the time to absorption given that a unit of carbon started in either the living microbial biomass or microbial necromass states. 
