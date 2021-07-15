# Bibliography

# Table of contents

* [Books](#Books)
* [Quadrotor simulation](#quadrotor-simulation)
* [Quadrotor swarms](#quadrotor-swarm)
  * [Thoery](#theory)
  * [Using Model Predictive Control](#using-model-predictive-control)
  * [Using Particle Swarm Optimization](#using-particle-swarm-optimization)
  * [Using Machine learning](#using-machine-learning)
* [Trajectory generation for quadrotors](#trajectory-generation-for-quadrotors)
* [Design and modeling for quadrotors](#design-and-modeling-for-quadrotors)
* [Swarm of UAV's and UGV's](#-swarm-of-UAVs-and-UGVs) 
  * [Using MPC](#using-mpc)
  * [Vision based](#vision-based)
* [SLAM](#slam)
* [Survery](#survey)
* [Model Predictive Control](#model-predictive-control)
* [Particle Swarm Optimization](#particle-swarm-optimization)
* [Positioning Systems](#positioning-system)
* [Failure mitigation in quadrotors](#failure-mitigation-in-quadrotors)
* [Quadrotors landing](#quadrotors-landing)
* [Quadrotors Applications](#quadrotors-applications)

### Books
---
* [Handbook of Unmanned Aerial Vehicles](https://link.springer.com/referencework/10.1007%2F978-90-481-9707-1) K. P. ValavanisGeorge, J. Vachtsevanos (2014).

### Quadrotor simulation
---
* [Comprehensive Simulation of Quadrotor UAVs Using ROS and Gazebo](https://www.researchgate.net/publication/262247993_Comprehensive_Simulation_of_Quadrotor_UAVs_Using_ROS_and_Gazebo)     J. Meyer, A. Sendobry, S. Kohlbrecher, U. Klingauf, O. von Stryk (2012).
* [RotorS – A Modular Gazebo MAV Simulator Framework](https://www.researchgate.net/publication/309291237_RotorS_-_A_Modular_Gazebo_MAV_Simulator_Framework) F. Furrer, M. Burri M. Achtelik, R.Siegwart (2016).
* [SwarmLab: a Matlab Drone Swarm Simulator](https://arxiv.org/abs/2005.02769) E. Soria, F. Schiano, D. Floreano (2020).
* [Evaluation Platform for Micro Aerial Indoor Swarm Robotics](https://www.researchgate.net/publication/343064227_Evaluation_Platform_for_Micro_Aerial_Indoor_Swarm_Robotics) C. Steup, S. Mostaghim, S. Mai (2016).
* [OpenUAV: A UAV Testbed for the CPS and Robotics Community](https://www.researchgate.net/publication/327191426_OpenUAV_A_UAV_Testbed_for_the_CPS_and_Robotics_Community) M. Schmittle, A. Lukina, L. Vacek, J. Das, C. P. Buskirk, S. Rees, J. Sztipanovits, R. Grosu, V. Kumar (2018).
* [AirSim: High-Fidelity Visual and Physical Simulation for Autonomous Vehicles](https://arxiv.org/abs/1705.05065) S. Shah, D. Dey, C. Lovett, A. Kapoor (2017).
* [Cyberbotics Ltd. Webots™: Professional Mobile Robot Simulation](https://journals.sagepub.com/doi/10.5772/5618) O. Michel (2004).
* [Design and use paradigms for Gazebo, an open-source multi-robot simulator](https://ieeexplore.ieee.org/document/1389727) N. Koenig, A. Howard (2003).

### Quadrotor swarms
---
* [The GRASP Multiple Micro UAV Testbed](https://citeseerx.ist.psu.edu/viewdoc/download?doi---10.1.1.169.1687&rep---rep1&type---pdf) N. Michael, D. Mellinger, Q. Lindsey, V. Kumar (2010).
* [Towards A Swarm of Agile Micro Quadrotors](http://roboticsproceedings.org/rss08/p28.pdf) A. Kushleyev, D. Mellinger, V. Kumar (2013).
* [Optimized flocking of autonomous drones in confined environments](https://robotics.sciencemag.org/content/3/20/eaat3536)G. Vásárhelyi, [Youtube](https://www.youtube.com/watch?v=E4XpyG4eMKE), [Code](https://github.com/csviragh/robotsim) (2018).
* [Outdoor flocking and formation flight with autonomous aerial robots](https://arxiv.org/abs/1402.3588) Gábor Vásárhelyi, Csaba Virágh, Gergő Somorjai, Norbert Tarcai, Tamás Szörényi, T. Nepusz, T. Vicsek (2014)
* [Flocking algorithm for autonomous flying robots](https://arxiv.org/abs/1310.3601)Csaba Virágh, Gábor Vásárhelyi, Norbert Tarcai, Tamás Szörényi, Gergő Somorjai, Tamás Nepusz, Tamás Vicsek (2014).
* [Swarms of micro aerial vehicles stabilized under a visual relative localization](https://www.researchgate.net/publication/286680349_Swarms_of_micro_aerial_vehicles_stabilized_under_a_visual_relative_localization ) M. Saska, J. Vakula and L. Přeućil (2014).
* [A swarm of flying smartphones](https://ieeexplore.ieee.org/document/7759270/) G. Loianno, Y. Mulgaonkar, C. Brunner, D. Ahuja, A. Ramanandan, M. Chari. S. Diaz, V. Kumar (2016).
* [Crazyswarm: A large nano-quadcopter swarm](https://www.researchgate.net/publication/318695162_Crazyswarm_A_large_nano-quadcopter_swarm) J. A. Preiss, W. Honig, G. S. Sukhatme, N. Ayanian (2017).
* [Design of small, safe and robust quadrotor swarms](https://ieeexplore.ieee.org/document/7139491) Y. Mulgaonkar, G. Cross, V. Kumar (2015).
* [A platform for aerial robotics research and demonstration: The Flying Machine Arena](https://www.sciencedirect.com/science/article/abs/pii/S0957415813002262) S. Lupashin,M. Hehn, M. W. Mueller, A. P. Schoellig, M. Sherback, R. D’Andrea (2014).
* [SFly: Swarm of micro flying robots](https://ieeexplore.ieee.org/document/6386281) M. Achtelik et al. (2012).
* [Visual Inertial Odometry Swarm: An Autonomous Swarm of Vision-Based Quadrotors](https://ieeexplore.ieee.org/document/8276634) A. Weinstein, A. Cho, G. Loianno, V. Kumar (2018)
* [Fast and In Sync: Periodic Swarm Patterns for Quadrotors](https://arxiv.org/abs/1810.03572) X. Du, C. E. Luis, M. Vukosavljev, A. P. Schoellig (2018).
* [Generation of collision-free trajectories for a quadrocopter fleet: A sequential convex programming approach](https://flyingmachinearena.org/wp-content/publications/2012/AugugliaroIROS2012.pdf)F. Augugliaro, A. P. Schoellig and R. D'Andrea (2012).

#### Theory

* [Flocking for Multi-Agent Dynamic Systems:Algorithms and Theory](https://authors.library.caltech.edu/28030/1/flocking-tr04-005.pdf) Reza Olfati-Saber (2006).
* [Collective motion](https://arxiv.org/abs/1010.5017) T. Vicsek, A. Zafeiris (2012).
* [Flocks, herds and schools: A distributed behavioral model](https://dl.acm.org/doi/10.1145/37402.37406) C. W. Reynolds (1987).
* [The influence of limited visual sensing on the Reynolds ﬂocking algorithm](https://infoscience.epfl.ch/record/264152?ln---fr) E. Soria, F. Schiano, D. Floreano (2019).
* [Novel Type of Phase Transition in a System of Self-Driven Particles](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.75.1226) T. Vicsek, A. Czirók, E. Ben-Jacob, I. Cohen, O. Shochet (1995).
* [Stable Flocking of Mobile Agents, Part I: Fixed Topology](http://research.me.udel.edu/~btanner/Papers/boids_smooth.pdf) H. G. Tanner, A. Jadbabaie, G. J. Pappas (2003)
* [Stable Flocking of Mobile Agents, Part II: Dynamic Topology](https://web.mit.edu/~jadbabai/www/papers/boids_nonsmooth.pdf) H. G. Tanner, A. Jadbabaie, G. J. Pappas (2003)

#### Using Model Predictive control (MPC)

* [Nonlinear Model Predictive Control for Multi-Micro Aerial Vehicle Robust Collision Avoidance](https://arxiv.org/abs/1703.01164) M. Kamel, J. Alonso-Mora, R. Siegwart, J. Nieto (2017).
* [Motion planning and control of formations of micro aerial vehicles](https://www.semanticscholar.org/paper/Motion-planning-and-control-of-formations-of-micro-Saska-Kasl/a8b2b317e16e609d0478dbbe339fac2760bda4a4) M. Saska, Z. Kasl, L. Preucil (2014).
* [Embedded Model Predictive Control of Unmanned Micro Aerial Vehicles](https://www.researchgate.net/publication/307599370_Embedded_Model_Predictive_Control_of_Unmanned_Micro_Aerial_Vehicles) T. Báča, G. Loianno, M. Saska (2016).
* [Nonlinear Model Predictive Formation Flight](https://ieeexplore.ieee.org/document/5109714) J. Shin and H. J. Kim (2009).
* [Formations of unmanned micro aerial vehicles led by migrating virtual leader](https://ieeexplore.ieee.org/document/7838801)M. Saska, T. Baca and D. Hert (2016).

#### Using Particle Swarm Optimization (PSO)

* [Autonomous deployment of swarms of micro-aerial vehicles in cooperative surveillance](https://www.semanticscholar.org/paper/Autonomous-deployment-of-swarms-of-micro-aerial-in-Saska-Chudoba/d05a0cba702ed85540ea0a973f03a6d47a743fe3) M. Saska, J. Chudoba, L. Precil, J. Thomas, G. Loianno, A. Tresnak, V. Vonásek, V. Kumar (2014).
* [Swarm Distribution and Deployment for CooperativeSurveillance by Micro-Aerial Vehicles](https://www.semanticscholar.org/paper/Swarm-Distribution-and-Deployment-for-Cooperative-Saska-Von%C3%A1sek/8d1f919e90e7dcd600c4b1cfa18ee6c1a765bddb) M. Saska, Vojtech Vonásek, J. Chudoba, Justin Thomas, Giuseppe Loianno, V. Kumar (2016).

#### Using machine learning

* [Learning Vision-based Cohesive Flight in Drone Swarms](https://arxiv.org/abs/1809.00543) F. Schilling, J. Lecoeur, F. Schiano, D. Floreano (2018).
* [Learning Vision-based Flight in Drone Swarms by Imitation](https://arxiv.org/abs/1908.02999) F. Schilling, J. Lecoeur, F. Schiano, D. Floreano (2019).
* [Deep Reinforcement Learning for Swarm Systems](https://arxiv.org/abs/1807.06613) M. Hüttenrauch, A. Šošić, G. Neumann (2019).
* [Guided Deep Reinforcement Learning for Swarm Systems](https://arxiv.org/abs/1709.06011), M. Hüttenrauch, A. Šošić, G. Neumann (2017).
* [Vision-based flocking in outdoor environments](https://arxiv.org/abs/2012.01245) F. Schilling, F. Schiano, D. Floreano (2020).

### Trajectory generation for quadrotors
---
* [Real-Time Trajectory Generation for Quadrocopters](https://ieeexplore.ieee.org/document/7128399) M. Hehn and R. D’Andrea (2015).
* [Trajectory Design and Control for Aggressive Formation Flight with Quadrotors](http://www.isrr-2011.org/ISRR-2011/Program_files/Papers/Turpin-ISRR-2011.pdf) M. Turpin, N. Michael, V. Kumar (2012).
* [Quadrocopter Trajectory Generation and Control](https://flyingmachinearena.org/wp-content/publications/2011/hehn_dandrea_trajectory_generation_control.pdf) M. Hehn, R. D’Andrea (2011).
* [CAPT: Concurrent assignment and planning of trajectories for multiple robots](https://journals.sagepub.com/doi/abs/10.1177/0278364913515307?journalCode---ijra) M. Turpin, N. Michael, V. Kumar (2014).
* [Polynomial Trajectory Planning for Aggressive Quadrotor Flight in Dense Indoor Environments](https://dspace.mit.edu/handle/1721.1/106840) C. Richter, A. Bry, N. Roy (2016).
* [Estimation, Control, and Planning for Aggressive Flight With a Small Quadrotor With a Single Camera and IMU](https://ieeexplore.ieee.org/document/7762111) G. Loianno, C. Brunner, G. McGrath and V. Kumar (2017).
* [A computationally efficient motion primitive for quadrocoptertrajectory generation](https://flyingmachinearena.org/wp-content/uploads/mueTRO15.pdf) M.W. Mueller, M. Hehn, R. D’Andrea (2015).
* [A computationally efficient algorithm for state-to-state quadrocopter trajectory generation and feasibility verification](https://www.semanticscholar.org/paper/A-computationally-efficient-algorithm-for-and-Mueller-Hehn/07dc99fa6e8c6a28e3b0ed88260fe015a8ba034f) M. W. Mueller, Markus Hehn, R. D'Andrea (2013).
* [Mixed integer programming for multi-vehicle
path-planning](https://www.researchgate.net/publication/240120004_Mixed_integer_programming_for_multi-vehicle_path-planning)
T. Schouweaaars (2001).
* [Multi-vehicle path planning for non-line of sight communication ](https://www.semanticscholar.org/paper/Multi-vehicle-path-planning-for-non-line-of-sight-Schouwenaars-Feron/cf69533aa757872a4af5b1bfbcf7a451603630ae)
T. Schouweaaars (2006).

### Design and modeling for quadrotors
---
* [Autonomous helicopter control using reinforcement learning policy search methods](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwiHv8WwyOfvAhVQTBoKHcyeDjUQFjACegQIAxAD&url=http%3A%2F%2Fciteseerx.ist.psu.edu%2Fviewdoc%2Fdownload%3Fdoi%3D10.1.1.465.8751%26rep%3Drep1%26type%3Dpdf&usg=AOvVaw3hWJFw8G9y_XLn6OP0Wkq8) J.A Bagnell, J. G. Schneider (2001).
* [Autonomous Helicopter Flight via Reinforcement Learning](https://papers.nips.cc/paper/2003/file/b427426b8acd2c2e53827970f2c2f526-Paper.pdf) H. Kim, M. Jordan, S. Sastry, A. Ng (2003).
* [An Application of Reinforcement Learning to Aerobatic Helicopter Flight](http://robotics.stanford.edu/~ang/papers/nips06-aerobatichelicopter.pdf) P. Abbeel et al (2007).
* [Neuroflight: next generation flight control firmware](https://hdl.handle.net/2144/41205) W. Koch, R. Mancuso, A. Bestavros (2019).
* [Control of a Quadrotor with Reinforcement Learning](https://arxiv.org/abs/1707.05110) J.Hwangbo, I. Sa, R. Siegwart, M. Hutter (2017).
* [Reinforcement Learning for UAV Attitude Control](https://arxiv.org/abs/1804.04154) W. Koch, R. Mancuso, R. West, A. Bestavros (2018).
* [PIXHAWK: A micro aerial vehicle design for autonomous flight using onboard computer vision  ](https://www.researchgate.net/publication/257522711_PIXHAWK_A_micro_aerial_vehicle_design_for_autonomous_flight_using_onboard_computer_vision) L. Meier, P. Tanskanen, L. Heng, G. Hee Lee, F. Fraundorfer, M. Pollefeys (2012).
* [PIXHAWK: A System for Autonomous Flight using Onboard Computer Vision](http://www-oldurls.inf.ethz.ch/personal/pomarc/pubs/MeierICRA11.pdf) L. Meier, P. Tanskanen, F. Fraundorfer, M. Pollefeys (2011).
* [PX4: A node-based multithreaded open source robotics framework for deeply embedded platforms](https://www.semanticscholar.org/paper/PX4%3A-A-node-based-multithreaded-open-source-for-Meier-Honegger/5f47298e5461a9cd29fc69c6393c5a3ad8bfd71a) L. Meier, D. Honegger, M. Pollefeys (2015).
* [PID vs LQ control techniques applied to an indoor micro quadrotor](https://ieeexplore.ieee.org/document/1389776) S. Bouabdallah, A. Noth and R. Siegwart (2004).
* [Design of a four-rotor aerial robot](https://eprints.qut.edu.au/83375) P. Pounds, R. Mahony, P. Hynes & J. Roberts (2002).
* [DroNet: Learning to Fly by Driving](http://rpg.ifi.uzh.ch/dronet.html) A. Loquercio, A.I. Maqueda, C.R. Del Blanco, D. Scaramuzza (2018).
* [An Open Source and Open Hardware Embedded Metric Optical FlowCMOS Camera for Indoor and Outdoor Applications](https://people.inf.ethz.ch/pomarc/pubs/HoneggerICRA13.pdf) D. Honegger, L. Meier, P. Tanskanen, M. Pollefeys (2013).
* [Design and Control of an Indoor Micro Quadrotor](https://www.researchgate.net/publication/4076717_Design_and_Control_of_an_Indoor_Micro_Quadrotor) S. Bouabdallah, P. Murrieri, R. Siegwart (2004).
* [Design and control of quadrotors with application to autonomous flying](https://infoscience.epfl.ch/record/95939?ln---fr) S. Bouabdallah (2007).
* [Fundamentals of Small Unmanned Aircraft Flight](https://www.semanticscholar.org/paper/Fundamentals-of-Small-Unmanned-Aircraft-Flight-Aileron/12df304fe865a9fc6c5a674e08f5a760e8448c65)J. D. Barton (2012).
* [Energy-efficient Autonomous Four-rotor Flying Robot Controlled at 1 kHz](https://www.researchgate.net/publication/224705216_Energy-efficient_Autonomous_Four-rotor_Flying_Robot_Controlled_at_1_kHz) D. Gurdan, J. Stumpf, M. Achtelik, K. Doth, G. Hirzinger, D. Rus (2007).
* [A Scripted Printable Quadrotor: Rapid Design and Fabrication of a Folded MAV](https://www.semanticscholar.org/paper/A-Scripted-Printable-Quadrotor%3A-Rapid-Design-and-of-Mehta-Rus/b4c8b98d19105472bdb4aad83cc573d6fb5770ba) A. Mehta, D. Rus, K. Mohta, Yash Mulgaonkar, M. Piccoli, V. Kumar (2013).
* [Computational Multicopter Design](https://cdfg.mit.edu/assets/files/copter.pdf) T. Du, A. Schulz, B. Zhu, B. Bickel, W. Matusik (2013).
* [The Navigation and Control technology inside the AR.Drone micro UAV](https://www.sciencedirect.com/science/article/pii/S1474667016438188) P.J. Bristeau, F. Callou, D. Vissière, N.Petit (2011).
* [CAD2RL: Real Single-Image Flight without a Single Real Image](https://arxiv.org/abs/1611.04201) F. Sadeghi, S. Levine (2017).
* [Learning Monocular Reactive UAV Control in Cluttered Natural Environments](https://arxiv.org/abs/1211.1690) S. Ross, N. Melik-Barkhudarov, K. S. Shankar, A. Wendel, D. Dey, J. A. Bagnell, M. Hebert (2012).
* [Quadrotor Helicopter Flight Dynamics and Control: Theory and Experiment](https://www.semanticscholar.org/paper/Quadrotor-Helicopter-Flight-Dynamics-and-Control%3A-Homann-Huang/ea719e5f4bde80e20e6e554eebe2a64c6b0df61b) G. M. Homann, H. Huang, S. L. Waslander, C. Tomlin (2007).
* [A 64mW DNN-based Visual Navigation Engine for Autonomous Nano-Drones](https://arxiv.org/abs/1805.01831) D. Palossi et al (2019).
* [Towards Open-Source , Printable Pico-Quadrotors](https://www.semanticscholar.org/paper/Towards-Open-Source-%2C-Printable-Pico-Quadrotors-Mulgaonkar-Kumar/b1575b2293d6933cd8f0cc8e828af4418d707f89) Y. Mulgaonkar, V. Kumar (2014).

### Swarm of UAV's and UGV's
---
#### using MPC
---
* [Navigation, localization and stabilization of formations of unmanned aerial and ground vehicles](https://www.researchgate.net/publication/261429814_Navigation_localization_and_stabilization_of_formations_of_unmanned_aerial_and_ground_vehicles) M. Saska et al (2013).
* [Coordination and navigation of heterogeneous MAV–UGV formations localized by a ‘hawk-eye’-like approach under a model predictive control scheme](https://www.semanticscholar.org/paper/Coordination-and-navigation-of-heterogeneous-by-a-a-Saska-Von%C3%A1sek/653e83fab826459a6a1af7c0495716740e234a49) M. Saska, V. Vonásek, T. Krajník, L. Preucil (2014).
* [Complex manoeuvres of heterogeneous MAV-UGV formations using a model predictive control](https://www.semanticscholar.org/paper/Complex-manoeuvres-of-heterogeneous-MAV-UGV-using-a-Spurn%C3%BD-B%C3%A1ca/45d6a5b0492d163c982b5aef11778b4f106eed7b) V. Spurný, T. Báca, M. Saska (2016).

#### vision based
---
* [A vision-guided autonomous quadrotor in an air-ground multi-robot system](https://www.semanticscholar.org/paper/A-vision-guided-autonomous-quadrotor-in-an-system-Li-Zhang/8b96bd403222b0a6d763c7d07888a346948e2770) W. Li, T. Zhang, K. Kühnlenz (2011).

### Simultaneous localization and mapping (SLAM)
---
* [Onboard IMU and monocular vision based control for MAVs in unknown in- and outdoor environments](https://ieeexplore.ieee.org/document/5980343) M. Achtelik, M. Achtelik, S. Weiss, R. Siegwart (2011).
* [Vision-Based Autonomous Mapping and Exploration Using a Quadrotor MAV](https://www.researchgate.net/publication/261353707_Vision-Based_Autonomous_Mapping_and_Exploration_Using_a_Quadrotor_MAV) F. Fraundorfer, L. Heng, D. Honegger, G. H. Lee, L. Meier, P. Tanskanen, M. Pollefeys (2012).
* [Ultimate SLAM? Combining Events, Images, and IMU for Robust Visual SLAM in HDR and High Speed Scenarios](https://arxiv.org/abs/1709.06310) A. R. Vidal, H. Rebecq, T. Horstschaefer, D. Scaramuzza (2017).
* [Cooperative localization and mapping of MAVs using RGB-D sensors](https://ieeexplore.ieee.org/document/7139761) G. Loianno, J. Thomas and V. Kumar (2015).
* [MAV-swarms: Unmanned aerial vehicles stabilized along a given path using onboard relative localization](https://www.researchgate.net/publication/282922149_MAV-swarms_Unmanned_aerial_vehicles_stabilized_along_a_given_path_using_onboard_relative_localization) M. Saska (2015).
* [Camera-Based Navigation of a Low-Cost Quadrocopter](https://jakobengel.github.io/pdf/engel12iros.pdf) J. Engel, J. Sturm, D. Cremers (2012).
* [System for deployment of groups of unmanned micro aerial vehicles in GPS-denied environments using onboard visual relative localization](https://core.ac.uk/reader/42585470) M. Saska, T. Baca, J. Thomas, J. Chudoba, L. Preucil, T. Krajnik, J. Faigl, G. Loianno, V. Kumar (2016).
* [A System for the Design and Development of Vision-based Multi-robot Quadrotor Swarm](http://oa.upm.es/45797/1/INVE_MEM_2014_246004.pdf) J. L. Sanchez-Lopez, J. Pestana, P. de la Puente, R. Suarez-Fernandezand P. Campoy ().
* [MAV Navigation through Indoor Corridors Using Optical Flow](http://rpg.ifi.uzh.ch/docs/ICRA10_zingg.pdf) S. Zingg, D. Scaramuzza, S. Weiss, R.Siegwart (2010).
* [Optimal surveillance coverage for teams of micro aerial vehicles in GPS-denied environments using onboard vision](https://link.springer.com/article/10.1007/s10514-012-9292-1)L. Doitsidis, S. Weiss, A. Renzaglia, M. W. Achtelik, E. Kosmatopoulos, R. Siegwart, D. Scaramuzza (2012).
* [UAV Formation Flight Based on Nonlinear Model Predictive Control](https://www.researchgate.net/publication/258382890_UAV_Formation_Flight_Based_on_Nonlinear_Model_Predictive_Control)Z. Chao, S.L. Zhou, L. Ming, W.G. Zhang (2012). 
* [Visual tracking and following of a quadrocopter by another quadrocopter](https://ieeexplore.ieee.org/document/6385635) K. E. Wenzel, A. Masselli and A. Zell (2012).
* [Vision-Controlled Micro Flying Robots From System Design to Autonomous Navigation and Mapping in GPS-Denied Environments](https://www.researchgate.net/publication/261512796_Vision-Controlled_Micro_Flying_Robots_From_System_Design_to_Autonomous_Navigation_and_Mapping_in_GPS-Denied_Environments) D. Scaramuzza, M. C. Achtelik, L. Doitsidis, F. Fraundorfer, E. Kosmatopoulos, A. Martinelli, M. W. Achtelik, M. Chli, S. Chatzichristofis, L. Kneip, D. Gurdan, L. Heng, G. Hee Lee, S. Lynen, L. Meier, M. Pollefeys, A. Renzaglia, R. Siegwart, J. C. Stumpf, P. Tanskanen, C. Troiani, S. Weiss

### Survey
---
* [A Survey on Aerial Swarm Robotics](https://ieeexplore.ieee.org/document/8424838) S. Chung, A. A. Paranjape, P. Dames, S. Shen, V. Kumar (2018).
* [Distributed Processing Applications for UAV/drones: A Survey](https://www.researchgate.net/publication/267811645_Distributed_Processing_Applications_for_UAVdrones_A_Survey) G. Chmaj, H. Selvaraj (2014).

### Positioning systems
---
* [3-D relative positioning sensor for indoor flying robots](https://www.researchgate.net/profile/Timothy_Stirling/publication/49964919_3-D_Relative_Positioning_Sensor_for_Indoor_Collective_Flying_Robots/links/58efb0f8a6fdcc25c8525730/3-D-Relative-Positioning-Sensor-for-Indoor-Collective-Flying-Robots.pdf) J. F. Roberts, T. Stirling. J. C. Zufferey, D. Floreano (2011).
* [Audio-based localization for swarms of micro air vehicles](https://ieeexplore.ieee.org/document/6907551) M. Basiri, F. Schill, D. Floreano and P. U. Lima (2014).
* [Audio-based Positioning and Target Localization for Swarms of Micro Aerial Vehicles](https://infoscience.epfl.ch/record/206769?ln---fr) M. Basiri (2015).
* [Audio-based Relative Positioning System forMultiple Micro Air Vehicle Systems](http://www.roboticsproceedings.org/rss09/p02.pdf) M. Basiri, F. Schill, D. Floreano, P. U.Lima (2014).
* [Practical Multirobot Localization System](https://link.springer.com/article/10.1007/s10846-014-0041-x) T. Krajník, M. Nitsche, J. Faigl, P. Vaněk, M. Saska, L. Přeučil, T. Duckett, M. Mejail (2014).
* [On-Board Relative Bearing Estimation for Teams of Drones Using Sound](https://infoscience.epfl.ch/record/217516?ln---fr) M. Basiri, F. Schill, P. Lima, D. Floreano (2016).
* [On-board Communication-based Relative Localization for CollisionAvoidance in Micro Air Vehicle teams](https://arxiv.org/abs/1609.08811) M. Coppola, K. McGuire, K.Y.W. Scheper, G. C.H.E. de Croon (2017).
* [A robot self-localization system using one-way ultra-wideband communication  ](https://www.semanticscholar.org/paper/A-robot-self-localization-system-using-one-way-Ledergerber-Hamer/b3e7132192d3131a9ff4ee21833eda574197bbe3) A. Ledergerber, M. Hamer, R. D'Andrea (2015).
* [Drone-aided Localization in LoRa IoT Networks](https://arxiv.org/abs/2004.03852) V. Delafontaine, F. Schiano, G. Cocco, A. Rusu, D. Floreano (2020).
* [Visual Tracking and Control of a Quadcopter Using a Stereo Camera System and Inertial Sensors](https://www.researchgate.net/publication/228962857_Visual_Tracking_and_Control_of_a_Quadcopter_Using_a_Stereo_Camera_System_and_Inertial_Sensors) M. Achtelik, T. Zhang, K. Kuhnlenz , M. Buss (2009).

### Failure mitigation in quadrotors.

* [Critical subsystem failure mitigation in an indoor UAV testbed](https://ieeexplore.ieee.org/document/6385910) M. W. Mueller, R. D’Andrea (2012).
* [Relaxed hover solutions for multicopters: application to algorithmic redundancy and novel vehicles](https://www.semanticscholar.org/paper/Relaxed-hover-solutions-for-multicopters%3A-to-and-Mueller-D%27Andrea/686c8e86208f0b2a2a0d7c1922db54b12ca1f2fa) M. W. Mueller, R. D’Andrea (2015).
* [Stability and control of a quadrocopter despite the complete loss of one, two, or three propellers](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjJ34a4vv3uAhUozoUKHcmxD3IQFjAEegQIAxAD&url=http%3A%2F%2Fhiperlab.berkeley.edu%2Fwp-content%2Fuploads%2F2018%2F05%2F2014_StabilityAndControlOfAQuadrocopterDespiteTheCompleteLossOfOneTwoOrThreePropellers.pdf&usg=AOvVaw2KGp_0i8u7wQJG-b-kCUs6) [Youtube](https://www.youtube.com/watch?v=t369aSInq-E) M. W. Mueller, R. D’Andrea (2014).

### Quadrotors landing
---
* [Vision-based Control of a Quadrotor for Perching on Lines](https://ieeexplore.ieee.org/document/6907309) K. Mohta, V. Kumar and K. Daniilidis (2014).
* [A Controller for Autonomous Landing of AR.Drone](http://robotics.fel.cvut.cz/pair14/wp-content/uploads/2014/09/pair14_submission-hrasko.pdf) R. Barták, A. Hraško, D. Obdržálek (2014).
* [Deep Reinforcement Learning Strategy for UAV Autonomous Landing on a Moving Platform](https://www.semanticscholar.org/paper/A-Deep-Reinforcement-Learning-Strategy-for-UAV-on-a-Rodriguez-Ramos-Sampedro/86d5f469f0f541f0b2223d2d3e80f22fb1d66af7) A. Rodriguez-Ramos, C. Sampedro, H. Bavle, P. D. L. Puente, P. Campoy (2019).
* [Autonomous landing on a moving vehicle with an unmanned aerial vehicle](https://www.researchgate.net/publication/330155244_Autonomous_landing_on_a_moving_vehicle_with_an_unmanned_aerial_vehicle) T. Baca et al (2019).
 
### Quadrotors applications
---
* [Quadrocopter Ball Juggling](https://flyingmachinearena.org/wp-content/uploads/2012/fma-publications/QuadrocopterBallJuggling.pdf) M. Muller, Se. Lupashin and Ra. D’Andrea (2012).
* [Quadrocopter Pole Acrobatics](https://idsc.ethz.ch/content/dam/ethz/special-interest/mavt/dynamic-systems-n-control/idsc-dam/People/bdario/brescianini_hehn_dandrea_pole_acrobatics.pdf) D. Brescianini, M. Hehn, R. D’Andrea (2013).
* [Building tensile structures with flying machines](https://www.semanticscholar.org/paper/Building-tensile-structures-with-flying-machines-Augugliaro-Mirjan/0bf536c0ec3dd56117e95faea78c1e012bd5affd) F. Augugliaro, A. Mirjan, F. Gramazio, M. Kohler, R. D'Andrea (2013).
* [Localization, Grasping, and Transportation of Magnetic Objects by a Team of MAVs in Challenging Desert-Like Environments](https://ieeexplore.ieee.org/document/8276269) G. Loianno, V. Spurny, J. Thomas, T. Baca, D. Thakur, D. Hert, R. Penicka, T. Krajnik, A. Zhou, A. Cho, M. Saska, V. Kumar (2018).
* [The application of small unmanned aerial systems for precision agriculture: a review](https://link.springer.com/article/10.1007/s11119-012-9274-5) C. Zhang, John M. Kovacs (2012).
* [Documentation of dark areas of large historical buildings by a formation of unmanned aerial vehicles using model predictive control](https://www.semanticscholar.org/paper/Documentation-of-dark-areas-of-large-historical-by-Saska-Kr%C3%A1tk%C3%BD/ee46ba99bebf912809ef0435dd1755860f0479e6) M. Saska, V. Krátký, V. Spurný, T. Báca (2017).
* [Opportunities and Challenges with Autonomous Micro Aerial Vehicles](https://link.springer.com/chapter/10.1007/978-3-319-29363-9_3) V. Kumar, N. Michael (2016).
* [Detecting, localizing, and tracking an unknown number of moving targets using a team of mobile robots](https://journals.sagepub.com/doi/10.1177/0278364917709507) P. Dames, Pratap Tokekar, V. Kumar (2017).
* [The use of unmanned aerial vehicles for an interdisciplinary undergraduate education: Solving quadrotors limitations](https://ieeexplore.ieee.org/document/7044443) C. Molina et al. (2014).
* [Cooperative quadrocopter ball throwing and catching](https://www.semanticscholar.org/paper/Cooperative-quadrocopter-ball-throwing-and-catching-Ritz-Mueller/6e4f6889b1ee90d9ce7d6b197073f5f7e09b632e) R. Ritz, M. W. Mueller, M. Hehn, R. D'Andrea (2012).

