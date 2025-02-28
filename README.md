**The repository contains the software and report for the project undertaken as coursework during my studies at University of Lincoln, Uk**

Teaching a robot to perform manuvers has been a very tidious task since the inception of this field. With the advancements taking place in the subject there have been certains conventional methods 
that have established themselves as the best suited for the task. Among those methods as DMPS and SEDS. This work is to appraise the useability of these methods to teach a robot to 
practice a trajectories passed to it. 

In the domain of robotics, learning from demonstrations is the method by which the robot acquire new skills. It can also be considered as imitating the teacher. 
From the scope of this work, in either of the cases here, the waypoints(cartesian points that coinside on the path to be traced by the robots) are passed via a xlsv, xsv or cvs file when using python for the usecase of DMPs and as a script file(.m file) when using MATLAB for the usecase of SEDs. The waypoint are the demonstrations passed by the teacher(user) in the form of a sequence of cartesian points 

**Dynamic Systems Motion Primitives :**  A mathematical framework for representing and generating complex motor actions. They are formalized as stable nonlinear attractor systems, which are highly flexible in creating complex rhythmic and discrete behaviors that can be adapted to changing environments.  They are easy to program complex and constrained motion.

**Stable Estimator for Dymanic Systems :** SEDS is a constrained optimization algorithm that formulates any arbitrary motion as a Mixture of Gaussian Functions. The constraints in SEDS guarantees the global asymptotic stability of a non-linear time-independent DS. This method is particularly useful for learning discrete robot motions from a set of demonstrations.

The reuslt of this project represents the different trajectories that were taught to a manipulator in a 2-D plane.  

**For in-depth explaination on the implementation of the software please refer to the project report. 
