# QPSO-LSTM
Prediction for OD distribution of dockless shared bicycles: a case study in Nanjing city

## Add
## Information of QPAO-LSTM model
The QPSO-LSTM model mainly includes two core algorithms, namely QPSO(quantum particle swarm optimization)(Sun et al. 2004) and LSTM(Long Short-Term Memory)(S. Hochreiter et al. 1997).
(1) QPSO is an improvement on traditional particle swarm optimization (PSO). It is inspired by the theory of quantum physics, that is, all particles have quantum behavior. Based on PSO, this algorithm eliminates the attribute of particle movement direction, that is, the update of particle position is independent of the previous particle position. It is more likely to obtain the global optimal solution or approximate optimal solution and determine the global optimal position(gbest) and part optimal position(pbest) of the particle by increasing the randomness of the particle's position. QPSO has been widely used in many fields such as function optimization. QPSO-LSTM model has some hyperparameters to be optimized, such as time step, number of hidden layer nodes, batch size, etc., as shown in Fig.1.

<p align="center"><img src="pic/Figure 5.jpg" width="65%"></p>








## How to run code 
