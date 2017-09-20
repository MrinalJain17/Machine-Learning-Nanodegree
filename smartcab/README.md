Train a Smart cab to drive
=====================

Applied reinforcement learning to build a simulated vehicle navigation agent. This project involved modeling a complex control problem in terms of limited available inputs, and designing a scheme to automatically learn an optimal driving strategy based on rewards and penalties.

Techniques implemented
-----------------------------------

1. Reinforcement Learning
2.  Q-Learning
3. Modeling + Model Tuning
4. Algebra

Result
---------

- The smart cab got an 'A+' rating in terms of Safety, meaning that it did not commit any traffic violations.
- In terms of Reliability, the cab got a rating of 'A', indicating that it reached its destination on time for at least 90% of the trips.

![Visualization of the Outcome](/outcome.png)

Instructions to Execute
--------------------------------

In the top directory (where the 'logs' folder is present), run the command - 

    python -m smartcab.agent

**Requirements:**

Python 2.7, with the following libraries - 
- Pygame
- NumPy
- matplotlib

To install Pygame on Python 2.7, run any one of the following - 

Mac: `conda install -c https://conda.anaconda.org/quasiben pygame`

Linux: `conda install -c https://conda.anaconda.org/tlatorre pygame`

Windows: `conda install -c https://conda.anaconda.org/prkrekel pygame`