---
layout: page
title: Workshops
show-avatar: False
--- 

Several pre-conference workshops are planned for Sunday, July 14.  They span a range of topics relevant to chemical plant operations and beyond, and are described below.

## Data Science Practitioner Experience and Industrial Tips and Tricks of the Trade (Half-day) 
### Organizers and Presenter(s): Leo Chiang, Ivan Castillo, Zhenyu Wang, and You Peng, The Dow Chemical Company

**Overview**: This half-day workshop aims to educate attendees on real-world experience in developing and implementing data science models to solve industry-relevant problems.  Specifically, we will dive into practical data science workflow from visualization, data preprocessing, model development to implementation and then summarize best practices on how to frame business opportunity as analytics problem to deliver value. After that, we will highlight several industry case studies to illustrate these concepts.  To wrap up, we will discuss some common misconceptions on data science and share future outlooks related to generative AI & the use of Large Language Models (LLMs) in industry. The target audience needs to have basic understanding and implementation experience of common data science methods. However, deep data science domain knowledge and programming proficiency is not needed. As such, we welcome industrial practitioners, academic researchers and students.
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 1.pdf" role="button">More Info</a>
</div>


## Application of Machine Learning in Accelerating MPC for Chemical Processes (Half-day) 
### Organizers and Presenter(s): Martin Klaučo, Patrik Valábek (Slovak University of Technology) 

**Overview**: The aim of this workshop is to provide hands-on experience for applications of machine learning tools in connection with control theory. Specifically, we introduce several possibilities as to how the MPC can be accelerated. We will provide a general overview and introduction to machine learning case studies suggesting suitable architectures and data preparation. Next, the workshop will introduce traditional MPC-mimicking procedures to generate approximate explicit control laws and procedures to general controllers posed as neural networks with stability guarantees. Case studies and examples will be tailored to chemical processes and problems arising in this domain. The workshop is primarily intended for graduate students and early-stage researchers and, as well as for all community members interested in hands-on applications of machine learning tools in process control. Furthermore, the workshop will be organized in interactive mode; hence, participants will gain experience in experiment preparation and coding examples.
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 2.pdf" role="button">More Info</a>
</div>


## Intelligent Alarm Management Techniques and Applications (Half-day) 
### Organizers and Presenter(s): Wenkai Hu (China University of Geosciences), Jiandong Wang (Shandong University of Science and Technology), Fan Yang (Tsinghua University), Tongwen Chen (University of Alberta), Sirish L. Shah (University of Alberta), Masaru Noda (Fukuoka University), Kevin Brown (Innovative Alarm Dynamics Ltd., Canada)

**Overview**: In the dynamic landscape of complex industrial facilities, effective alarm management is paramount to ensuring operational efficiency, safety, and overall system reliability. However, in real industries, alarm systems usually suffer from degraded performance due to alarm overloading and the presence of alarm floods. Thus, there is a strong need to develop and deploy intelligent alarm management tools, so as to improve the alarm system performance and reduce operators’ workload. This workshop is meticulously crafted to address the unique challenges posed by the intricacies of modern industrial alarm systems. The workshop's primary objective is to empower industry professionals with the data analytic tools to navigate the complexities of alarm monitoring, ensuring not only compliance with industrial standards but also enhancing operational efficiency.
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 3.pdf" role="button">More Info</a>
</div>


## Optimal Operation and Advanced Control using Decomposition and Simple Elements (Full-day) 
### Organizers and Presenter(s): Sigurd Skogestad (Professor, NTNU, Norway) and Krister Forsman (Control Specialist, Perstorp Co., Sweden) 

**Overview**: How can you control a complex plant effectively using simple elements with a minimal amount of modelling? How can you put optimization into the control layer? Industry has been using simple and effective as “advanced regulatory control” schemes for almost 100 years. The objective of the workshop is to provide a systematic approach for designing such control systems. The approach is illustrated on numerous real industrial applications. The target audience includes both practicing control engineers as well as PhD students and teachers from academia.
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 4.pdf" role="button">More Info</a>
</div>


## End-to-end process monitoring techniques and case studies: Hands-on workshop (Full-day) 
### Presenter: Lidia Auret (StoneThree)

**Overview**: Practical process monitoring in industry requires fault detection, identification, diagnosis, and the implementation of process recovery actions. Algorithmic design and automation of all these steps are required if the future promise of more autonomous plants is to be realised. However, theoretical research in process monitoring is overwhelmingly focused on the task of fault detection. End-to-end process monitoring (Auret and Louw, 2023a) encompasses the fully automated workflow from detection to implementation of the appropriate corrective action in a process. This workshop will discuss and demonstrate a framework for improved experimentation of end-to-end process monitoring approaches. 
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 5.pdf" role="button">More Info</a>
</div>

## Optimal Control in Julia with JuMP and InfiniteOpt (Full-day) 
### Presenter: Joshua Pulsipher (University of Waterloo)

**Overview**: This workshop will be an interactive tutorial on how to model complex nonlinear, continuous-time optimal control problems via InfiniteOpt.jl and JuMP.jl. Leveraging a unifying abstraction for infinite-dimensional optimization (InfiniteOpt) problems, InfiniteOpt.jl is a Julia-based open-source software package that builds upon JuMP.jl to provide an intuitive symbolic modeling environment for many problem classes in dynamic, PDE-constrained, and stochastic optimization. Moreover, its extensibility allows researchers to make their cutting-edge techniques accessible to a wide audience of individuals. All these aspects make InfiniteOpt.jl a powerful tool for tackling advanced optimal control problems. This workshop is intended for researchers (both academic and industrial) and practitioners interested in solving optimal control problems. The workshop will be accessible for those with limited experience modeling optimization problems in Julia and will feature a collection of interactive Jupyter worksheets to actively engage those attending. Researchers with an advanced knowledge of JuMP.jl will also benefit from learning how to use InfiniteOpt.jl to deploy their research methods.
<div class="text-center">
  <a class="btn btn-warning btn-lg" href="./assets/docs/Workshop 6.pdf" role="button">More Info</a>
</div>

<!-- 
# Workshops
Pre-conference workshops will be offered at AdCONIP 2022. Please see the list below.

- [Workshop 1: Making reinforcement learning a practical technology for industrial control](#workshop-1-making-reinforcement-learning-a-practical-technology-for-industrial-control)
  + August 7th 2022 - 8AM to 1PM
  + [See detailed workshop schedule]({% link _pages/RL_workshop.md %})
- [Workshop 2: Process Data Analytics and Network or Flowsheet Reconstruction](#workshop-2-process-data-analytics-and-network-or-flowsheet-reconstruction)
  + August 7th 2022 - 2PM to 6:30PM

# Workshop 1: Making reinforcement learning a practical technology for industrial control
### August 7th 2022 - 8AM to 1PM

## Overview
Reinforcement learning (RL) is an emerging technology in process systems engineering (PSE) [1,2]. The objective in RL is to generate an optimal “policy” in a stochastic environment [3]. This general formulation makes RL appealing for both control and operational decision-making tasks, notably, without a system model [2]. Despite the enthusiasm surrounding RL, there are also reasons to be skeptical of its viability. For example, RL does not have strong stability or constraint satisfaction guarantees, and it is notoriously data-hungry. Recent work at the intersection of RL and PSE strives to mitigate these issues and ultimately make RL more reliable, scaleable, and interpretable [4–7]. This workshop aims to engage academics and industrial practitioners in both the machine learning and controls communities with a lively discussion on the challenges and opportunities surrounding real-world RL.

## Learning Outcomes
By the end of this workshop, the attendees will:
1. Learn the foundations of reinforcement learning and its relation to control-theoretic concepts.
2. Understand how reinforcement learning can address the needs of industrial practitioners.
3. Obtain a solid understanding of current challenges and opportunities in reinforcement learning research for process systems engineering applications.

## Description
The following topics will be discussed in this workshop.

1. General introduction
  + Foundations of reinforcement learning
  + Relationship to more familiar control-theoretic concepts

2. Prior art in industry
  + Discuss the needs in industry and the potential impact of reinforcement learning
  + Discuss challenges of deploying reinforcement learning algorithms in the process industries

3. State of the art in deep reinforcement learning for process systems engineering
  + Series of individual presentations touching on the following themes:
  + Stability and constraints in reinforcement learning
  + Sample efficient and robust learning techniques
  + Reinforcement learning with partial knowledge of the system
  + Controller architectures and system integration
  + Other topics generally geared towards the challenges and opportunities in RL for process systems engineering

## Schedule
A detailed schedule is available in [this page]({% link _pages/RL_workshop.md %}).

## Expected Audience
The expected audience is researchers, graduate students, and industrial practitioners primarily with a controls background who are interested in practical aspects of deploying reinforcement learning techniques.

## Organizers
- Nathan Lawrence, University of British Columbia, Canada (lawrence@math.ubc.ca)
- Philip Loewen, University of British Columbia, Canada (loew@math.ubc.ca)

## Speakers
### Philip Loewen, University of British Columbia, Canada (loew@math.ubc.ca)
<img src="/assets/img/loewen.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Philip D. Loewen** received the Ph.D. degree in mathematics from The University of British Columbia (UBC), for work on nonsmooth problems of dynamic optimization. After post-doctoral stays at the Centre de Recherches Mathematiques, Montreal, and the Department of Electrical Engineering, Imperial College, London, he returned to UBC as a faculty member in Mathematics in 1987. His research interests include optimal control, optimization, convex and nonsmooth analysis, and engineering applications.
<br>
### Jay Lee, Korea Advanced Institute of Science and Technology, Korea, South Korea (jayhlee@kaist.ac.kr)
<img src="/assets/img/jay.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Jay H. Lee** obtained his B.S. degree in Chemical Engineering from the University of Washington, Seattle, in 1986, and his Ph.D. degree in Chemical Engineering from California Institute of Technology, Pasadena, in 1991. From 1991 to 1998, he was with the Department of Chemical Engineering at Auburn University, AL, as an Assistant Professor and an Associate Professor. From 1998-2000, he was with School of Chemical Engineering at Purdue University, West Lafayette, and then with the School of Chemical Engineering at Georgia Institute of Technology, Atlanta from 2000-2010. Since 2010, he is with the Chemical and Biomolecular Engineering Department at Korea Advanced Institute of Science and Technology (KAIST), where he was the department head from 2010-2015. He is currently a Professor, Associate Vice President of International Office, and Director of Saudi Aramco-KAIST CO2 Management Center at KAIST. He published over 180 manuscripts in SCI journals with more than 13000 Google Scholar citations. His research interests are in the areas of system identification, state estimation, robust control, model predictive control, and reinforcement learning with applications to energy systems, biorefinery, and CO2 capture/conversion systems.
<br>
### Biao Huang, University of Alberta, Canada (biao.huang@ualberta.ca)
<img src="/assets/img/biao.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Biao Huang** received his Ph.D. degree in Process Control from the University of Alberta, Canada, in 1997. He held MSc degree (1986) and BSc degree (1983) in Automatic Control from the Beijing University of Aeronautics and Astronautics. He is currently a Professor with the University of Alberta, IEEE Fellow, and Fellow of the Canadian Academy of Engineering. His research interest includes Process Control, Process Data Analytics and Machine Learning. He is the Editor-in-Chief for IFAC Journal Control Engineering Practice, Subject Editor for Journal of the Franklin Institute, and Associate Editor for Journal of Process Control.
<br>
### Panagiotis Petsagkourakis, Illumina, England (ppetsag@gmail.com)
<img src="/assets/img/panos.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Panos** received his chemical engineering degree (silver medal award- summa cum laude) from the National Technical University of Athens (Greece) in 2015. He then joined the University of Manchester and the School of Chemical Engineering and Analytical Science for to pursue his PhD degree in 2015. In February 2019, he joined University College London as a Research fellow for the EPSRC project on cognitive chemical manufacturing. He also joined Imperial College London as visiting researcher. Panos joined the L&SE Young Members Forum in 2019 as university representative.
<br>
### Ehecatl Antonio del Rio Chanona, Imperial College London, England (a.del-rio-chanona@imperial.ac.uk)
<img src="/assets/img/antonio.jpeg" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Antonio del Rio Chanona** is head of the Optimisation and Machine Learning for Process Systems Engineering group at the Department of Chemical Engineering, Imperial College London. Antonio received his MEng from UNAM in Mexico, and his PhD from the University of Cambridge where he was awarded the Danckwerts-Pergamon Prize for the best doctoral thesis of his year. He received the EPSRC fellowship to adopt automation and intelligent technologies into bioprocess scaleup and industrialization and has received awards from the International Federation of Automatic Control (IFAC), and the Institution of Chemical Engineers (IChemE) in recognition for research in areas of process systems engineering, industrialisation of bioprocesses, and adoption of intelligent and autonomous learning algorithms to chemical engineering. 
Antonio’s main research interests include Reinforcement Learning, Data-Driven Optimization, Control and Hybrid Modelling.
<br>
### Mario Zanon, IMT School for Advanced Studies Lucca, Italy (mario.zanon@imtlucca.it)
<img src="/assets/img/mario.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Mario Zanon** received his Master's degree in Mechatronics from the University of Trento, and the Diplôme d'Ingénieur from the Ecole Centrale Paris, in 2010. After research stays at the KU Leuven, University of Bayreuth, Chalmers University, and the University of Freiburg he received the Ph.D. degree in Electrical Engineering from the KU Leuven in November 2015. He held a Post-Doc researcher position at Chalmers University until the end of 2017, after which he became Assistant Professor and, from 2021, Associate Professor at the IMT School for Advanced Studies Lucca. His research interests include reinforcement learning, numerical methods for optimization, economic MPC, optimal control and estimation of nonlinear dynamical systems in particular for aerospace and automotive applications.
<br>
### Sebastien Gros, Norwegian University of Science and Technology, Norway (sebastien.gros@ntnu.no)
<img src="/assets/img/gros.jpg" style="float: left; padding: 0.5em; margin-right: 1.0em; width: 200px">

**Sebastien Gros** received his Ph.D degree from EPFL, Switzerland, in 2007. After a journey by bicycle from Switzerland to the Everest base camp in full autonomy, he joined a R&D group hosted at Strathclyde University focusing on wind turbine control. In 2011, he joined the university of KU Leuven, where his main research focus was on optimal control and fast NMPC for complex mechanical systems. He joined the Department of Signals and Systems at Chalmers University of Technology, Göteborg in 2013, where he became associate Prof. in 2017. He is now full Prof. and Head of the department of Engineering Cybernetic, NTNU, Norway and affiliate Prof. at Chalmers. His main research interests includes numerical methods, real-time optimal control, reinforcement learning, stochastic optimal control, Markov Decision Processes, and the optimal control of energy-related applications. He is currently focusing on the optimization of smart houses with ambitious and unique experiments.

#### Joint Presentations:
- Panagiotis Petsagkourakis & Ehecatl Antonio del Rio Chanona will give joint presentations.
- Mario Zanon & Sebastien Gros will give joint presentations.

### References
- [1] Rui Nian, Jinfeng Liu, and Biao Huang. A review on reinforcement learning: Introduction and applications in industrial process control. Computers & Chemical Engineering, page 106886, 2020.

- [2] Joohyun Shin, Thomas A. Badgwell, Kuang-Hung Liu, and Jay H. Lee. Reinforcement Learning –Overview of recent progress and implications for process control. Computers & Chemical Engineering, 127:282–294, 2019. ISSN 00981354. doi: 10.1016/j.compchemeng.2019.05.029.

- [3] Richard S Sutton and Andrew G Barto. Reinforcement learning: An introduction. MIT press, 2018.

- [4] Panagiotis Petsagkourakis, Ilya Orson Sandoval, Eric Bradford, Dongda Zhang, and Ehecatl Antoniodel Rio-Chanona. Reinforcement learning for batch bioprocess optimization. Computers & Chemical Engineering, 133:106649, 2020.

- [5] Mario Zanon and Sébastien Gros. Safe reinforcement learning using robust mpc. IEEE Transactions on Automatic Control, 66(8):3638–3652, 2020.

- [6] Haeun Yoo, Boeun Kim, Jong Woo Kim, and Jay H. Lee. Reinforcement learning based optimal control of batch processes using Monte-Carlo deep deterministic policy gradient with phase segmentation. Computers & Chemical Engineering, 144:107133, 2021. ISSN 00981354. doi: 10.1016/j.compchemeng.
2020.107133.

- [7] Nathan P Lawrence, Michael G Forbes, Philip D Loewen, Daniel G McClement, Johan U Backstrom, and R Bhushan Gopaluni. Deep reinforcement learning with shallow controllers: An experimental application to PID tuning. Control Engineering Practice, 121:105046, 2022.

---

# Workshop 2: Process Data Analytics and Network or Flowsheet Reconstruction
### August 7th 2022 - 2PM to 6:30PM

## Overview
The following topics will be discussed in this workshop. Each topic will be accompanied by one or more industrial case study to convey the utilitarian value of the learning, discovery and diagnosis from process data.

- Overview of the broad analytics area with emphasis on its use in the process industry. Basic definitions and introduction to supervised and unsupervised learning: simple regression, classification and clustering; Data visualization methods (in the temporal as well as the spectral domains).
- Multivariate methods for data analysis: Principal Component Analysis (PCA) / Singular Value Decomposition (SVD) and its variants for steady-state model identification and reconstruction of conservation networks.
- Alarm data analysis: Detection and removal of nuisance alarms; root-cause analysis of alarms and alarm floods.
- Causal discovery and network reconstruction: Causality concepts and definitions; Methods for detecting cause-effect links and reconstructing graphical / network models from data. 


## Description

We are currently at the cusp of the fourth industrial revolution (4IR) or Industry 4.0 that is poised to reshape all the sectors of economy and society with an unprecedented depth and breadth. Emerging technologies including complex organization and systems, smart sensing, industrial robotics, industrial wireless communications, industrial Internet-of-Things (IIoT), Internet-of-Moving-Things (IoMT), industrial cloud, industrial big data and cyber-physical systems (CPS) have become hotspots of research and innovation globally. 

Process data analytic methods rely on the notion of sensor fusion whereby data from many sensors and alarm tags are combined with process information, such as physical connectivity of process units, to give a holistic picture of health of an integrated plant. The fusion of information from such disparate sources of data is the key step in devising methodologies for smart strategies for process data analytics.

In the context of the application of analytics in the process industry, the objective in this workshop is to introduce participants to tools, techniques and a framework for seamless integration of information from process and alarm databases complemented with process connectivity information. The discovery of information from such diverse and complex data sources can be subsequently used for process and performance monitoring including alarm rationalization, root cause diagnosis of process faults, hazard and operability (Hazop) analysis, safe and optimal process operation. Such multivariate process data analytics involves information extraction from routine process data, that is typically non-categorical (as in numerical process data from sensors), plus categorical (or non-numerical or qualitative and binary) data from Alarm and Event (A&E) logs combined with process connectivity or topology information that can be inferred from the data through causality analysis or as obtained from piping and instrument diagrams of a process. The later refers to the capture of material flow streams in process units as well information flow-paths in the process due to control loops. 

Highly interconnected process plants are now common and the analysis of root causes of process abnormality including predictive risk analysis is non-trivial. It is the extraction of information from the fusion of process data, alarm and event data and process connectivity that should form the backbone of a viable process data analytics strategy and this will be the main focus of this workshop. Representing process behaviour using networks is visually appealing and easy to understand. Process flowsheets and first-principles knowledge have been used to represent the interconnectivity among different unit operations and in process simulation and optimization.  Analogously, other forms of networks derived from measured data are useful in applications such as fault diagnosis, monitoring and control. Finally, for efficient and informative analytics, data analysis is ideally carried out in the temporal as well as spectral domains, on a multitude and NOT singular sensor signal time-trends to detect process abnormality, ideally in a predictive mode.

The emphasis in this workshop will be on tools and techniques that help in the process of understanding data and discovering information that will lead to predictive monitoring, reconstructing network representations from data and diagnosis of process faults.

Typical process data analytic methods require the execution of following steps:

1. Data quality assessment including outlier detection and noise filtering
2. Data visualization and segmentation
3. Process and performance monitoring including root cause detection of faults
4. Alarm data analysis
5. Data-based process topology discovery and validation

## Desired prerequisites for attendees
Basic knowledge of statistics and linear algebra

## Target audience
The intended audience for this workshop would be industrial practitioners of control including vendors working in the area of on-line data logging and archiving, graduate students with interests in statistical learning and data science and academics.

## Course Schedule
**Time:** 4.5 hours (half day) on **7th August 2022**.

- **2:00PM** Registration and introduction of speakers and participants
- **2:10PM** Introduction to process data analytics (SLS)
- **3:15PM** Coffee break
- **3:30PM** Alarm data analytics (SLS)
- **4:00PM** Reconstructing conservation networks from data (SN)
- **5:15PM** Causal discovery and network reconstruction from data (AKT)
- **6:30PM** Questions + General discussion


## Speakers

### Sirish Shah (UAlberta)
<img src="/assets/img/sirish.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Sirish L. Shah** is Emeritus Professor at the University of Alberta where he held the NSERC-Matrikon-Suncor-iCORE Senior Industrial Research Chair in Computer Process Control from 2000 to 2012. 
The main area of his current research is process and performance monitoring, system identification and design, analysis and rationalization of alarm systems. He has co-authored three books, the first titled “Performance Assessment of Control Loops: Theory and Applications”, a second book titled book titled “Diagnosis of Process Nonlinearities and Valve Stiction: Data Driven Approaches” and a more recent brief monograph titled, “Capturing Connectivity and Causality in Complex Industrial Processes”.

### Shankar Narasimhan (IIT Madras)
<img src="/assets/img/shankar.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Shankar Narasimhan** is the M.S. Ananth Institute Chair Professor in the Department of Chemical Engineering at IIT Madras. He obtained his Bachelor’s degree from IIT Madras in 1982 and PhD degree from Northwestern University, USA in 1987.  His major research interests are in the areas of Data Mining, Process Design and Optimization and Fault Detection and Diagnosis (FDD).  He is the co-author of several important papers and a book on Data Reconciliation and Gross Error Detection. He has held visiting positions at the Centre for Automatic Control in Nancy, France, Purdue University, Clarkson University and Texas Tech University in USA and the University of Alberta in Canada. He has also spent summer internships at Engineers India Ltd., R&D Centre in Gurgaon, Honeywell Technology Solutions Ltd., R&D Centre at Bangalore, and ABB Global Services Ltd., Bangalore as part of high-level industry-academia interactions. He is the co-founder of Gyan Data Pvt. Ltd. in 2011, which specializes in using data analytics for manufacturing excellence and GITAA Pvt. Ltd., in 2018, which offers training in advanced data analytics, machine learning and artificial intelligence. He is a Fellow of the Indian National Academy of Engineering. 

### Arun K. Tangirala (IIT Madras)
<img src="/assets/img/arun.png" style="float: left; padding: 0.5em; margin-right: 1.0em; width:200px">

**Arun K. Tangirala** holds a Bachelors in Chemical Engineering and a Doctoral degree in Process Control from the University of Alberta. He is a Professor at the Department of Chemical Engineering, IIT Madras. His research is concerned with multi-disciplinary problems of causality analysis, network reconstruction, control loop performance monitoring, multiscale identification, sparse optimization (compressive sensing)-based identification, systems biology and modern applications of data science. He is a recipient of several prestigious teaching & research awards and international fellowships. In addition, he has held visiting appointments at the University of Delaware, Technical University of Munich and Tsinghua University. He was awarded the Young Faculty Recognition Award in 2010 and the 2014 Institute Research and Development Award by IIT Madras. He is the author of a comprehensive classroom text on "Principles of System Identification: Theory and Practice". He is currently the Editor-in-Chief of the Journal of Institution of Engineers India: Series E (Chemical and Textile Engineering), an Associate Editor of the ASME Journal of Dynamics, Measurement and Control and an Associate Editor of Control Engineering Practice. He is also an active member of ASME, IEEE, AIChE, CSChE and is a faculty associate of the Robert Bosch Centre for Data Science and Artificial Intelligence at IIT Madras.


 -->
