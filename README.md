# Modeling the public transport network in Milan: an ABM Approach
Final project for the Simulation and Modeling course.
The presented notebooks and data are the outputs of the final project for the [Simulation and Modeling course](https://didattica.unibocconi.eu/ts/tsn_anteprima.php?cod_ins=20599&anno=2022&IdPag=6163) taught by professor [Alessia Melegaro](https://scholar.google.com/citations?user=K0yyigMAAAAJ&hl=it&oi=ao), spring semester 2022.

Authors:
- Claudia Sessa [Github](https://github.com/sesclaud) | [Linkedin](https://www.linkedin.com/in/claudiasessa/)
- Cecilia Terraneo
- Davide Nobile [Github](https://github.com/davnobile) | [Linkedin](https://www.linkedin.com/in/davide-nobile-0938301b1/)
- Arturo Mario Bagnara [Github](https://github.com/arturo-bagnara) | [Linkedin](https://www.linkedin.com/in/arturo-mario-bagnara/)

Mobility is one of the key factors for a large city to become a welldeveloped metropolitan area and simulations in this field have become crucial in understanding cities’ issues. This project aims to measure the efficiency of Milan’s public transport network, by simulating the flow of individuals through an agent-based model (ABM) and identifying the differences in agents’ behavior following shocks and interventions. The choice of an ABM allows to model the complex transportation system in a granular way, as the sum of interactions of the individuals’ travel behaviours. Furthermore, it permits to explore how agents interact with the environment, and how, through such interactions, aggregate patterns emerge. This simulator, integrated with other tools, could support decision makers in evaluating changes to the lines and optimizing the network. We show two cases studies in this paper.

This repository contains the following files:

Report: This file extensively covers the aims, steps undertaken and results of our analysis;

0_preliminary_steps.ipynb: This notebook contains some data cleaning and data manipulation that were undertaken in order to build the network for our model;

1_network_generation.ipynb: This notebook contains the generation process of the graph and the creation of the minute-by-minute timetable;

2_agents_model_final.ipynb: This notebook contains the creation of the model, which consists of the method for the generation of the sythetic population, the Agent class, the model, a function to run a simulation from start to finish and several functions for the analysis of the simulation's results;

killing_agents.py: This is an auxiliary file for the easy import of all functions defined in previous notebooks;

Experiment_1.ipynb: This notebook contains the creation of the network for experiment 1, the simulation itself and the analysis of the results;

Experiment_2.ipynb: This notebook contains the creation of the network for experiment 2, the simulation itself and the analysis of the results;

data: Folder containing all the data necessary to run the notebooks;

pickle_ag & pickle_ag2: Folders containing pickle files with 10 sets of 25000 agents, generated for experiment 1 and 2 respectively.
