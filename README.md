# Production Policy Simulation

This repository contains a discrete-event simulation project that compares two production policies in a manufacturing system.

The project focuses on production planning and control, with the goal of determining which policy leads to shorter order processing times and shorter waiting times.

## Project Goal

The main goal of this project is to compare two production policies and evaluate which one performs better over time.

The research question is:

Which production policy should be chosen so that the processing time of orders will be shorter?

## Production Policies

The simulation compares two alternatives:

### Policy A

Each production team specializes in a specific type of pipe.

### Policy B

Each production team can work on all types of pipes.

In Policy B, jobs are assigned using the SPT rule — Shortest Processing Time first.

## Repository Contents

production-policy-simulation/
├── Production Policy Simulation.ipynb
├── SimClasses.py
├── SimFunctions.py
├── SimRNG.py
├── Project_Group09_דוב וויזמן וניר צ'אוסר.pptx
├── README.md
└── .gitignore

## Files Description

### Production Policy Simulation.ipynb

The main Jupyter Notebook of the project.
It contains the simulation model, experiments, results, and analysis comparing the production policies.

### SimClasses.py

Contains the main simulation classes, including event calendar, queues, resources, entities, and statistics collectors.

### SimFunctions.py

Contains helper functions for initializing the simulation, scheduling events, and clearing statistics between simulation runs.

### SimRNG.py

Contains random number generation and random-variate generation functions used in the simulation.

### Project_Group09_דוב וויזמן וניר צ'אוסר.pptx

The project presentation.
It explains the background, research question, assumptions, simulation results, conclusions, and follow-up questions.

## Main Conclusion

Based on the simulation results, Policy A is preferable in the long run.

Policy A performs better because:

* Production times become shorter.
* Waiting times become shorter.
* The system becomes more efficient over time.

## How to Run the Project

1. Clone the repository:

git clone [https://github.com/Nir-Chauser/production-policy-simulation.git](https://github.com/Nir-Chauser/production-policy-simulation.git)

2. Enter the project folder:

cd production-policy-simulation

3. Install Jupyter Notebook if needed:

pip install notebook

4. Open the notebook:

jupyter notebook "Production Policy Simulation.ipynb"

5. Run the notebook cells in order.

## Requirements

Python 3.x

Jupyter Notebook

## Authors

Nir Chausser

Dov Weizman

Group 9
