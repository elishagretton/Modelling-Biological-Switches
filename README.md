# Modelling Biological Switches using Differential Equations

During my integrated Masters in Mathematics at the University of Sheffield, I completed a year-long research project on biological switches. More specifically, the mathematics behind this behaviour and how we can reflect this using various types of mathematical models.

Some key questions to consider:
* What is a biological switch?
* Why are they important to biological processes?
* How do you use mathematics to create these accurate models?

In this project, I leveraged data visualisation libraries in Python such as matplotlib and seaborn. The numPy library is also used frequently.

## Table of Contents
1. [Introduction](#introduction)
2. [Key Objectives](#key-objectives)

### *Introduction*

#### What is a Biological Switch? 
A biological switch is used to model any general decision-making mechanism in biological systems. Due to environmental changes, these systems must respond quickly and make a decision about its consequent actions. In other words, the behaviour of the system **switches** to compensate for this change. Once a system fully switches its behaviour, we can say it has reached a decision. In mathematical terms, the system is in equilibrium until another change in the system occurs.

Some examples of biological switches are:
* Honeybees when faced with the decision of relocating hives. Bees alter their behaviour by forming a unique dance to persuade other bees to relocate to their chosen hive.
* Gene regulatory proteins respond to signals to control the release of certain genes in the body.
   
#### Why are biological switches important? ####
Biological switches are important to model for a number of reasons. Some of these reasons are:
* Increased understanding of complex behaviours and interactions between cells in biological systems.
* Abiity to make predictions about dynamic features in biological systems such as switching point, reaction time, trajectory of decision.
* Create more accurate mathematical models to reflect observed behaviours.

Computational algorithms such as in-built differential equations solvers and other numerical techniques like the Milstein method, form the basis behind these models and furthermore increase the computational speed when generating results.

### *Key Objectives*

Biological switch behaviour can easily be simulated in Python using various types of differential equations. 

The key objectives for this investigation are as follows:
1. The use of ordinary differential equations (ODEs), delay differential equations (DDEs), stochastic differential equations (SDEs), and stochastic delay differential equations (SDDEs) when modelling a biological switch.
2. The behaviour that is simulated with each model through useful visualisations such as Time Vs Concentration diagrams, nullclines, and phase portraits.
3. Using statistics and testing to form accurate conclusions from the data about two main characteristics of a biological switch: switching time and predictability of its end point.


