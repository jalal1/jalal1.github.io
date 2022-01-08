---
layout: page
title: Projects
---
### **Research Projects**
**T-thinker: Parallel Mining of Large Maximal Quasi-Cliques**\
In this project, we propose a parallel solution for mining maximal quasi-cliques that is able to fully utilize CPU cores. Our solution utilizes divide and conquer to decompose the workloads into independent tasks for parallel mining, and we addressed the problem of (i) drastic load imbalance among different tasks and (ii) difficulty in predicting the task running time and the time growth with task-subgraph size, by (a) using a timeout-based task decomposition strategy, and by (b) utilizing a priority task queue to schedule long-running tasks earlier for mining and decomposition to avoid stragglers.\
[GitHub](https://github.com/yanlab19870714/Tthinker)

**Realistic Transport Simulation Using MATSim and Open Data**\
MATSim is the state-of-the-art open source software for agent-based transport simulation, intended for use to evaluate transportation planning models. A standard approach to use MATSim is to conduct a user survey about their day-plans of travel, from which a synthetic dataset of agents' day-plans for an entire region is generated for transport simulation. The simulation output can be used for various evaluations, such as congestion conditions of road segments and their peak hours.

Work includes:
- Plan generation using machine learning utilizing a small survey data and open data.
- MATSim configuration and parameter tuning for the transportation simulation of the city of Birmingham, AL.
- The study of mode-rich scenarios involving public transit, e-scooter, etc.
- Using Python ( 70% ), Jupyter Notebook ( 20% ) and Java ( 10% )


### **Course Projects**
1. JTO\
JTO is a social network platform for gym goers, where they can update their training progress, upload images and share posts with friends.\
Using Flask, Python, SQLAlchemy and PostgreSQL.\
[GitHub](https://github.com/jalal1/JTO)

2. Simple Encryption on AWS\
File encryption tool to encrypt files on AWS using OpenSSL.\
Using Using Python, tkinter, OpenSSL and AWS\
[GitHub](https://github.com/jalal1/simple-encryption-aws)

3. Air Quality Index - Covid 19\
Data visualization project, to show how COVID-19 affects the air quality index in the United States. It shows the data in March and April for the years 2019 and 2020.\
Using D3.js and JavaScript\
[GitHub](https://github.com/jalal1/AQI_covid19)