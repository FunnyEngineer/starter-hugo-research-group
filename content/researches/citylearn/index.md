---
title: CityLearn
date: 2022-08-05T20:52:17.988Z
summary: "CityLearn is an open source OpenAI Gym environment for the
  implementation of Multi-Agent Reinforcement Learning (RL) for building energy
  coordination and demand response in cities. Its objective is to facilitiate
  and standardize the evaluation of RL agents such that different algorithms can
  be easily compared with each other. Try it out using
  our [example](https://drive.google.com/drive/folders/1oxdAMLTRA1qsLuwJbd5oo9y\
  EmSjm6i64?usp=sharing) in Google Colab! More details and installation on
  GitHub: <https://github.com/intelligent-environments-lab/CityLearn>"
draft: false
featured: false
tags:
  - Reinforcement Learning
categories:
  - Reinforcement Learning
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
---
CityLearn is an open source OpenAI Gym environment for the implementation of Multi-Agent Reinforcement Learning (RL) for building energy coordination and demand response in cities. Its objective is to facilitiate and standardize the evaluation of RL agents such that different algorithms can be easily compared with each other. Try it out using our [example](https://drive.google.com/drive/folders/1oxdAMLTRA1qsLuwJbd5oo9yEmSjm6i64?usp=sharing) in Google Colab! 

Districts and cities have periods of high demand for electricity, which raise electricity prices and the overall cost of the power distribution networks. Flattening, smoothening, and reducing the overall curve of electrical demand helps reduce operational and capital costs of electricity generation, transmission, and distribution networks. Demand response is the coordination of electricity consuming agents (i.e. buildings) in order to reshape the overall curve of electrical demand. CityLearn allows the easy implementation of reinforcement learning agents in a multi-agent setting to reshape their aggregated curve of electrical demand by controlling the storage of energy by every agent. Currently, CityLearn allows controlling the storage of domestic hot water (DHW), and chilled water (for sensible cooling and dehumidification). CityLearn also includes models of air-to-water heat pumps, electric heaters, solar photovoltaic arrays, and the pre-computed energy loads of the buildings, which include space cooling, dehumidification, appliances, DHW, and solar generation.

More details and installation on GitHub: https://github.com/intelligent-environments-lab/CityLearn

Also check out the annual CityLearn Challenge http://www.citylearn.net

The 2022 edition is organized in collaboration with AICrowd, sign up here: <https://www.aicrowd.com/challenges/neurips-2022-citylearn-challenge>

**Key Publications**

Vázquez-Canteli JR, Kämpf J, Henze G, Nagy Z. CityLearn v1. 0: An OpenAI gym environment for demand response with deep reinforcement learning. InProceedings of the 6th ACM International Conference on Systems for Energy-Efficient Buildings, Cities, and Transportation 2019 Nov 13 (pp. 356-357).

Vazquez-Canteli JR, Henze G, Nagy Z. MARLISA: Multi-agent reinforcement learning with iterative sequential action selection for load shaping of grid-interactive connected buildings. InProceedings of the 7th ACM international conference on systems for energy-efficient buildings, cities, and transportation 2020 Nov 18 (pp. 170-179).

Vázquez-Canteli JR, Dey S, Henze G, Nagy Z. CityLearn: Standardizing research in multi-agent reinforcement learning for demand response and urban energy management. arXiv preprint arXiv:2012.10504. 2020 Dec 18.