---
layout: page
title: RL Workshop Schedule
subtitle: 2022 AdCONIP Reinforcement Learning Workshop - Making reinforcement learning a practical technology for industrial control
show-avatar: False
---

Note: **All times in PST (Pacific Time)**.

# Time: 8:00-8:55

<div class="text-center">
<h2>Foundations of Reinforcement Learning</h2>
<b>Philip D. Loewen</b>
<br>
<i>loew@math.ubc.ca</i>
<br>
The University of British Columbia, Canada
</div>

**Abstract:** Reinforcement Learning is a modern framework that addresses the central challenge of control systems design: given some dynamic environment in which choices are possible, build a mapping from observations to actions that guarantees desirable behaviour. This talk will survey the mathematical and algorithmic fundamentals of RL and indicate their counterparts in control systems design. The focus will be on "what" and "how" rather than "why". Thus there will be more equations than videos, all carefully selected to provide a smooth on-ramp for non-specialists to understand and appreciate the contributions described in the later presentations of the workshop.

<img src="/assets/img/loewen.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Philip D. Loewen** received the Ph.D. degree in mathematics from The University of British Columbia (UBC), for work on nonsmooth problems of dynamic optimization. After post-doctoral stays at the Centre de Recherches Mathematiques, Montreal, and the Department of Electrical Engineering, Imperial College, London, he returned to UBC as a faculty member in Mathematics in 1987. His research interests include optimal control, optimization, convex and nonsmooth analysis, and engineering applications.

<br>

(10 minute break)

# Time: 9:05–9:50

<div class="text-center">
<h2>Deep reinforcement learning for industrial process control applications — a practitioner’s perspective on the current state and future prospects</h2>
<b>Tom Badgwell (work with R. Donald Bartusiak)</b>
<br>
<i>tom.badgwell@gmail.com</i>
<br>
Collaborative Systems Integration, USA
</div>

**Abstract:** Reinforcement Learning (RL) is a machine learning technology in which a computer agent learns, through trial and error, the best way to accomplish a particular task. The recent development of Deep Reinforcement Learning (DRL) technology, in which deep learning networks are used to parameterize the RL agent’s policy and value functions, has enabled superhuman performance for some tasks, most especially games such as chess and GO. Researchers have devised DRL algorithms specifically for continuous control problems, and this has led many in the process control community to wonder what impact DRL technology will have on our industry. This presentation builds on previous analysis efforts on the appropriateness of DRL by providing a specific list of requirements for industrial process control technology: 

- Ease of use
- Consistency of implementation
- Offset-free control in the presence of model mismatch and disturbances
- Stability and performance guarantees
- Flexibility to solve a large number of closely related control problems

DRL technology will be assessed with respect to each requirement, exposing existing deficiencies, useful research directions, and potential solutions. It will be shown that DRL technology is not likely to replace currently used Proportional-Integral-Derivative (PID) or Model-Predictive Control (MPC) algorithms, however it may prove useful in managing control systems by helping to tune controllers, advising operators during upsets or transient operations, and by managing plant-wide disturbances such as diurnal changes and weather events. A final section will present ideas on how best to integrate aspects of DRL and MPC technologies, for the benefit of both.

<img src="/assets/img/badgwell.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Thomas A. (Tom) Badgwell** is the Chief Technology Officer at Collaborative Systems Integration, an Austin-based startup providing systems integration services and software products for Open Process Automation (O-PAS) based systems. He earned a BS degree from Rice University and MS and PhD degrees from the University of Texas at Austin, all in Chemical Engineering, and he is registered as a Professional Engineer in Texas. Tom’s career has focused on modeling, optimization, and control of chemical processes, with past positions at Setpoint, Fisher/Rosemount, Rice University, Aspen Technology, and ExxonMobil. He is a Fellow of the American Institute of Chemical Engineers (AIChE) and a past Director of the Computing and Systems Technology (CAST) Division, from which he received the Computing Practice Award in 2013. He has served as an Associate Editor for the Journal of Process Control and as a Trustee of the Computer Aids in Chemical Engineering (CACHE) Corporation.

<br>

# Time: 9:50 – 10:35

<div class="text-center">
<h2>Combining Reinforcement Learning and Model Predictive Control: Fundamentals and Recent
Research Results</h2>
<b>Sebastien Gros<sup>1</sup>, Mario Zanon<sup>2</sup></b>
<br>
<i>sebastien.gros@ntnu.no; mario.zanon@imtlucca.it</i>
<br>
1. Norwegian University of Science and Technology, Norway<br>
2. IMT School for Advanced Studies Lucca, Italy
</div>

**Abstract:** Model Predictive Control (MPC) is a well-established, formal tool for the control of systems with constraints and/or nonlinear dynamics. MPC relies heavily on a model of the system at hand, and the closed-loop performance of MPC depends on the accuracy of that model. In that context, the classic paradigm of using a model that best fits the data provides no guarantee of good closed-loop performance of MPC. Reinforcement Learning (RL) is a well-known set of tools for generating optimal policies without relying on a model of the system at hand. While it achieved several spectacular and highly mediated successes, RL nonetheless struggles to provide the same level of formal guarantees as formal control tools, such as MPC, can. In this talk, we will discuss an approach that seamlessly and harmoniously combines MPC and RL into an optimal control tool that inherits the strengths of both. We will first discuss the fundamentals of this approach, its formal motivations and some early associated results. Then, we will briefly discuss recent research results that establish the potential of this combination to, among other things, introduce formal safety and stability in RL.

<img src="/assets/img/gros.jpg" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Sebastien Gros** received his Ph.D degree from EPFL, Switzerland, in 2007. After a journey by bicycle from Switzerland to the Everest base camp in full autonomy, he joined a R&D group hosted at Strathclyde University focusing on wind turbine control. In 2011, he joined the university of KU Leuven, where his main research focus was on optimal control and fast NMPC for complex mechanical systems. He joined the Department of Signals and Systems at Chalmers University of Technology, Göteborg in 2013, where he became associate Prof. in 2017. He is now full Prof. and Head of the department of Engineering Cybernetic, NTNU, Norway and affiliate Prof. at Chalmers. His main research interests includes numerical methods, real-time optimal control, reinforcement learning, stochastic optimal control, Markov Decision Processes, and the optimal control of energy-related applications. He is currently focusing on the optimization of smart houses with ambitious and unique experiments.

<br>

<img src="/assets/img/mario.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Mario Zanon** received his Master's degree in Mechatronics from the University of Trento, and the Diplôme d'Ingénieur from the Ecole Centrale Paris, in 2010. After research stays at the KU Leuven, University of Bayreuth, Chalmers University, and the University of Freiburg he received the Ph.D. degree in Electrical Engineering from the KU Leuven in November 2015. He held a Post-Doc researcher position at Chalmers University until the end of 2017, after which he became Assistant Professor and, from 2021, Associate Professor at the IMT School for Advanced Studies Lucca. His research interests include reinforcement learning, numerical methods for optimization, economic MPC, optimal control and estimation of nonlinear dynamical systems in particular for aerospace and automotive applications.

<br>

(10 minute break)

# Time: 10:45 – 11:30

<div class="text-center">
<h2>Recent advances and applications on reinforcement learning: from constraints to supply chains</h2>
<b>Panagiotis Petsagkourakis<sup>1</sup>, Antonio del Rio Chanona<sup>2</sup></b>
<br>
<i>ppetsag@gmail.com; a.del-rio-chanona@imperial.ac.uk</i>
<br>
1. Illumina, England<br>
2. Imperial College London, England
</div>

**Abstract:** The emerging field of reinforcement learning (RL) has led to remarkable empirical results in rich data domains like robotics and strategy games. However, so far, few adoptions have been made into process engineering. This seminar will aim to introduce and showcase the use of RL in process control and operations. In the first part of the seminar, we will talk about a framework to deal with safety critical constraints in policy optimization, as present algorithms mostly use difficult-to-tune penalty parameters which fail to reliably satisfy state constraints or present guarantees only in expectation. On the second part of the talk, we will highlight recent developments on the use of distributional RL for safe and fast learning of RL agents in practical implementations.

<img src="/assets/img/panos.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Panagiotis (Panos) Petsagkourakis1** received his chemical engineering degree (silver medal award- summa cum laude) from the National Technical University of Athens (Greece) in 2015. He then joined the University of Manchester and the School of Chemical Engineering and Analytical Science for to pursue his PhD degree in 2015. In February 2019, he joined University College London as a Research fellow for the EPSRC project on cognitive chemical manufacturing. He also joined Imperial College London as visiting researcher. Panos joined the L&SE Young Members Forum in 2019 as university representative.

<br>

<img src="/assets/img/antonio.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Ehecatl Antonio del Rio Chanona** is head of the Optimisation and Machine Learning for Process Systems Engineering group at the Department of Chemical Engineering, Imperial College London. Antonio received his MEng from UNAM in Mexico, and his PhD from the University of Cambridge where he was awarded the Danckwerts-Pergamon Prize for the best doctoral thesis of his year. He received the EPSRC fellowship to adopt automation and intelligent technologies into bioprocess scaleup and industrialization and has received awards from the International Federation of Automatic Control (IFAC), and the Institution of Chemical Engineers (IChemE) in recognition for research in areas of process systems engineering, industrialisation of bioprocesses, and adoption of intelligent and autonomous learning algorithms to chemical engineering. 
Antonio’s main research interests include Reinforcement Learning, Data-Driven Optimization, Control and Hybrid Modelling.

<br>

# Time: 11:30 - 12:15

<div class="text-center">
<h2>RL for autonomous tuning of advanced controllers subject to constraints</h2>
<b>Biao Huang (work with Oguzhan Dogru)</b>
<br>
<i>biao.huang@ualberta.ca</i>
<br>
University of Alberta, Canada
</div>

**Abstract:** Autonomous tuning of advanced process controllers is presented. For safe exploration, constraints on both control parameters and control variables are considered. To reduce agent training time, offline model-based training and online process-based tuning are proposed. Simulations, pilot-scale experiments and implementation through industrial scale Delta V distributed control systems are demonstrated.

<img src="/assets/img/biao.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Biao Huang** received his Ph.D. degree in Process Control from the University of Alberta, Canada, in 1997. He held MSc degree (1986) and BSc degree (1983) in Automatic Control from the Beijing University of Aeronautics and Astronautics. He is currently a Professor with the University of Alberta, IEEE Fellow, and Fellow of the Canadian Academy of Engineering. His research interest includes Process Control, Process Data Analytics and Machine Learning. He is the Editor-in-Chief for IFAC Journal Control Engineering Practice, Subject Editor for Journal of the Franklin Institute, and Associate Editor for Journal of Process Control.

<br>

# Time: 12:15 - 13:00

<div class="text-center">
<h2>Learning and Model Predictive Control: Similarities, Differences and Paths Forward</h2>
<b>Jay Lee</b>
<br>
<i>jayhlee@kaist.ac.kr</i>
<br>Korea Advanced Institute of Science and Technology, Korea
</div>

**Abstract:** Since Alan Turing's remarkable foresight of creating a machine that simulates the 'adult brain' starting from the 'child mind' through a computer algorithm that educates through rewards and punishments, reinforcement learning (RL) has been at the forefront of many academic fields including psychology, computer science, and control. With recent advancement of deep learning and GPU-computing as well as well-publicized success stories like the Alpha-Go, it is enjoying a renaissance of popularity and offers opportunities for applications with commercial impacts. RL and control originated from different fields but they both address the same basic problem of making sequential decisions in an uncertain, dynamic environment to maximize/minimize a long-term objective function. In this presentations, similarities and differences between reinforcement learning and optimal control will be brought to attention and some ideas will be shared on how they can be brought to complement and support each other in solving complex industrial decision problems. Some exemplary applications expected to benefit significantly from the use of RL concepts and methods will be presented, including batch process control, energy planning, and materials design.

<img src="/assets/img/jay.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Jay H. Lee** obtained his B.S. degree in Chemical Engineering from the University of Washington, Seattle, in 1986, and his Ph.D. degree in Chemical Engineering from California Institute of Technology, Pasadena, in 1991. From 1991 to 1998, he was with the Department of Chemical Engineering at Auburn University, AL, as an Assistant Professor and an Associate Professor. From 1998-2000, he was with School of Chemical Engineering at Purdue University, West Lafayette, and then with the School of Chemical Engineering at Georgia Institute of Technology, Atlanta from 2000-2010. Since 2010, he is with the Chemical and Biomolecular Engineering Department at Korea Advanced Institute of Science and Technology (KAIST), where he was the department head from 2010-2015. He is currently a Professor, Associate Vice President of International Office, and Director of Saudi Aramco-KAIST CO2 Management Center at KAIST. He published over 180 manuscripts in SCI journals with more than 13000 Google Scholar citations. His research interests are in the areas of system identification, state estimation, robust control, model predictive control, and reinforcement learning with applications to energy systems, biorefinery, and CO2 capture/conversion systems.
