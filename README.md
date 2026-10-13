# SEIRD_model
SEIRD Epidemic Model (NetLogo)  
An agent-based simulation of the SEIRD epidemic model built with NetLogo. This model extends the classic SEIR structure by accounting for disease-related mortality.  

Compartments BreakdownS   
(Susceptible): Healthy individuals who can contract the disease.  
E (Exposed): Infected individuals during the incubation period (not yet contagious).  
I (Infectious): Contagious individuals capable of transmitting the virus.  
R (Recovered): Individuals who have recovered and gained immunity.  
D (Deceased): Individuals who died from the infection.  

How to Run  
Install NetLogo (version 6.0 or higher).  
Clone this repository or download the SEIRD.nlogo file.  
Open NetLogo and load SEIRD.nlogo (File > Open).  
Click the Setup button to initialize the population.  
Click the Go button to run the simulation.  

Parameters & Controls  
Adjust the interface sliders to experiment with:  
Transmission Rate / Contact Rate: Controls how quickly the virus spreads.  
Incubation Period: Time spent in the Exposed ($E$) compartment.  
Recovery Rate vs. Mortality Rate: Determines the ratio of individuals moving to $R$ or $D$.
