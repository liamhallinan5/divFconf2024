+++
title = "Speakers"
+++

## Speakers 

### Morning session (11:00am--1:00pm)

#### 1. Introduction: Simon Godsill (11:00am--11:10am)

#### 2. Keynote: Guillaume Hennequin (CBL) (11:10am--11:40am)
[Group website](https://cbl.eng.cam.ac.uk/hennequin/)

*The best-laid plans of mice and men...*

My group's research in computational neuroscience is broadly concerned with how brains control behaviour. In many settings, behaviour involves sequences of actions that need careful planning. In this talk, I will present our recent work on planning in recurrent neural networks (Jensen et al., Nat. Neurosci, 2024). I will show that decision-making networks trained with the ability to decide for themselves (i) when to pause and ‘think’, and (ii) what to do with those ‘thoughts’, recapitulate key aspects of human planning in a flexible navigation task. We show that this network-level theory of planning is supported by neural recordings from the hippocampus of rodents. I will strive to make this accessible for the whole of DivF, and to wrap up in 25 min, but then again, the best-laid plans of mice and men...


#### 3. Aliaksandra Shysheya & Cristiana Diaconu (CBL) (11:40am -- 12:00pm)

*On conditional diffusion models for PDE simulations*

Modelling partial differential equations (PDEs) is of crucial importance in science and engineering. Some of the most common tasks include 1) forecasting, where the aim is to predict future states based on an initial one, as well as 2) inverse problems, such as data assimilation (DA), with the goal of reconstructing an aspect of the PDE (i.e. coefficient, initial condition, full trajectory, etc.) given some partial observations of the solution to the PDE. However, most previous numerical and machine learning approaches that target forecasting cannot be applied out-of-the-box for data assimilation.

Recently, diffusion models have emerged as a powerful tool for conditional generation, being able to flexibly incorporate observations without retraining. In this work, we perform a comparative study of score-based diffusion models for forecasting and assimilation of sparse observations. In particular, we focus on diffusion models that are either presented with the conditional information during training, or conditioned after unconditional training. We address the shortcomings of previous work and develop methods that are able to successfully tackle the combination of forecasting and data assimilation, a task commonly encountered in real-world scenarios such as weather modelling.


#### 4. Jeff Wang (Control)  (12:00pm--12:20pm)

*Control of an unknown physical system with a stability guarantee*

In the era of machine learning, learning to control is gaining popularity. However, it is difficult to guarantee the stability of a system with a learnt controller. In this presentation, we will go through a controller design process for a simple physical system whose dynamics is unknown. Our design is data-driven and we guarantee stability by borrowing tools from passivity-based control. We think this presentation provides a new perspective on learning with guarantees.

#### 5. Carl Ashworth (CBL) (12:20pm--12:40pm)

*The Neural Dynamics of Endogenous Pain Regulation*

Pain is regulated by endogenous pain modulatory pathways, which connect the brain to the spinal cord and up and down-regulate the transmission of nociceptive information. These control pathways are hypothesized to become dysfunctional in chronic pain, making understanding their dynamics vital. The most important source of this control is the Rostral Ventromedial Medulla (RVM). As the lowest part of the brainstem, this region is a bottleneck through which signals from higher-order brain regions must pass before reaching the spinal cord. To date, research into the function of the RVM has been almost entirely pharmacological and anatomical, and a computational model of ongoing RVM dynamics does not currently exist that can explain the behaviour of RVM neurons individually or as a population.

In this talk, I will show how periodic Gaussian processes (GPs) can provide new insights into the ongoing dynamics of RVM neurons. I will present evidence for the periodicity of a subset of RVM cells (ON- and OFF-cells) and discuss the implications of periodic dynamics on the connectivity and function of RVM in pain regulation, opening the door for simulations of population behaviour in this region.


#### 6. Florian Fischer (MIL) (12:40pm--1:00pm)

*Simulating User Movements in VR Interaction*

Automated biomechanical testing has great potential for the development of VR applications, as initial insights into user behaviour can be gained in silico early in the design process. In particular, it allows prediction of user movements and ergonomic variables, such as fatigue, prior to conducting user studies. In combination with mathematical methods for predicting control strategies, biomechanical models provide a powerful tool to simulate interaction movements in a time-continuous and holistic manner. In this talk, I present a novel, optimisation-driven perspective on movement-based interaction in VR, discuss the potential of control theoretic and RL-based user models for Human-Computer Interaction and interface optimisation, and present SIM2VR, a system that uses these methods to align user simulation with a given VR application. SIM2VR, for the first time, enables training simulated users directly in the same VR application that real users interact with, and constitutes a decisive step towards automated biomechanical testing in VR.


### Afternoon talks (2:00pm--4:00pm)

#### 1. Keynote: Hatice Gunes (2:00pm--2:30pm)
[Bio](https://www.cl.cam.ac.uk/~hg410/)

[Group website](https://cambridge-afar.github.io/)

*Robotic Coaches for Mental Wellbeing: From the Lab to the Real World*

In recent years, the field of socially assistive robotics for promoting wellbeing has witnessed a notable surge in research activity. It is increasingly recognized within the realms of social robotics and human-robot interaction (HRI) that robots have the potential to function as valuable instruments for evaluating, sustaining, and enhancing various aspects of human wellbeing, including physical, mental, and emotional health.
At the Cambridge Affective Intelligence and Robotics Lab ( https://cambridge-afar.github.io/), our work on creating robotic coaches for mental wellbeing started in 2019 with a 5-year funding from the UK Engineering and Physical Sciences Research Council (EPSRC). Since then, we have engaged in a series of studies, employing an iterative approach that integrates user-centric design, testing, and deployment in both controlled laboratory settings and real-world contexts, while learning from failure and mistakes and striving to continuously improve our robotic coaches. We have done this by 1) collaborating with experienced human coaches and professionals who currently deliver these interventions, 2) gaining insights into the expectations and perceptions of potential users, and collecting valuable feedback from them, and 3) developing real-time AI and data-driven affective adaptation mechanisms for longitudinal deployment.
In this talk, I will share our journey in developing robotic coaches for mental wellbeing and transitioning them from the controlled lab environment to real-world settings and will illustrate the challenges and opportunities of social robotics for promoting wellbeing with a number of case studies, with insights for short- and long-term adaptation, and highlight the perceptions and expectations of prospective users to guide future research in this area.
 
#### 2. John Bronskill (CBL) (2:30pm--2:50pm)

*LLM Processes: Numerical Predictive Distributions Conditioned on Natural Language*

Machine learning practitioners often face significant challenges in formally integrating their prior knowledge and beliefs into predictive models. Moreover, the expertise needed to integrate this prior knowledge into probabilistic modeling typically limits the application of these models to specialists. Our goal is to build a regression model that can process numerical data and make probabilistic predictions at arbitrary locations, guided by natural language text which describes a user's prior knowledge. Large Language Models (LLMs) provide a useful starting point for designing such a tool since they 1) provide an interface where users can incorporate expert insights in natural language and 2) provide an opportunity for leveraging latent problem-relevant knowledge encoded in LLMs that users may not have themselves. We start by exploring strategies for eliciting explicit, coherent numerical predictive distributions from LLMs. We examine these joint predictive distributions, which we call LLM Processes, over arbitrarily-many quantities in settings such as forecasting, multi-dimensional regression, black-box optimization, and image modeling. We investigate the practical details of prompting to elicit coherent predictive distributions, and demonstrate their effectiveness at regression. Finally, we demonstrate the ability to usefully incorporate text into numerical predictions, improving predictive performance and giving quantitative structure that reflects qualitative descriptions.


#### 3. Erez Li (Control) (2:50pm--3:10pm)

*How does the physiology of a cell affect its response to antimicrobial treatments?*

Antimicrobial resistance is drawing significant attention nowadays as many bacterial infections have become increasingly difficult to treat with conventional antibiotics. Meanwhile, phage therapy has re-emerged as a promising alternative. While extensive research has focused on the molecular characterisation of antimicrobial agents such as antibiotics and phages, little is known about how bacterial physiological heterogeneity influences treatment outcomes. Given that the effectiveness of both antibiotics and phages intrinsically depends on the physiological state of the bacteria, we ask: 1) How does intrinsic physiological heterogeneity lead to heterogeneous response towards treatments? 2) How does heterogeneous response affect post-treatment recovery? In this talk, we present an integrated approach that combines a high throughput microfluidics platform and a machine learning based data processing pipeline to analyse response and recovery of individual bacterial cells, addressing these questions.


#### 4. Yaman Kindap (SigProc) (3:10pm--3:30pm)

*Non-Gaussian Stochastic Differential Equation Models for Dynamical Systems*

Many natural and engineering systems evolve continuously in time, exhibiting complex behaviors such as abrupt changes and extreme events. However, most practical models rely on discrete-time, Gaussian assumptions, which can oversimplify real-world dynamics, leading to the loss of critical insights. This talk introduces non-Gaussian stochastic processes as a more flexible framework for capturing both the latent trends and rare phenomena in such systems. Using Levy processes—an extension of Brownian motion—we will explore how these models provide a natural prior for continuous-time, heavy-tailed dynamics. The tutorial will cover the basic principles and simulation techniques for Levy processes and demonstrate their application to stochastic differential equations (SDEs) for modeling complex systems. Finally, we will discuss efficient methods for inference and learning in non-Gaussian SDEs, offering a powerful approach for engineering challenges involving unpredictable and extreme behavior, from financial shocks to severe weather events.



#### 5. Term Welcome Address: Simon Godsill (3:30pm--4:00pm)

