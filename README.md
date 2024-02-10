# SEL3-2024
Tutorials used in the Ghent University course: Software Engineering Lab 3 (SEL3) 2024.

The general goal of the course's project is to optimize controllers for an in-silico brittle star robot. The simulation model and environment are provided by the [Bio-inspired Robotics Testbed (BRT)](https://github.com/Co-Evolve/brt).

Tutorials:
* [brb_brittle_star_environment.ipynb](tutorials/brb_brittle_star_environment_tutorial.ipynb): covers the creation and usage of the BRT's brittle star simulation environment.
* [brb_brittle_star_cpg_tutorial.ipynb](tutorials/brb_brittle_star_cpg_tutorial.ipynb): covers the background and implementation of Central Pattern Generators. Provides a case study in which a CPG model is applied to generate a simplified rowing gait for the brittle star robot.
* [brb_brittle_star_qlearning_tutorial.ipynb](tutorials/brb_brittle_star_qlearning_tutorial.ipynb): covers the implementation and application of Q-Learning (a canonical reinforcement learning algorithm). Provides a case study in which Q-Learning is applied to optimize a controller for the brittle star.
* [brb_brittle_star_quality_diversity_tutorial.ipynb](brb_brittle_star_quality_diversity_tutorial.ipynb): covers the background of Quality-Diversity algorithms. Provides an implementation of the MAP-Elites algorithm and applies it to generate brittle star gaits.

  