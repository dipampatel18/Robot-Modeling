# Robot-Modeling

## Course Project for ENPM 662 : Introduction to Robot Modeling

Articulated robots with multiple degrees of freedom, such as humanoid robots, have become popular research platforms in robotics and artificial intelligence. Such robots can perform complex motions, including the balancing, walking, and kicking skills. The robot must keep its balance, self-collisions and collisions with obstacles in the environment must be avoided and, if applicable, the trajectory of the end-effector must follow the constrained motion of a manipulated object in Cartesian space. Humanoid service robots performing complex object manipulation tasks need to plan whole-body motions that satisfy a variety of constraints: These constraints and the high number of degrees of freedom make the whole-body motion planning for humanoids a challenging problem. The design of complex dynamic motions is achievable only using robot kinematics, which is an application of geometry to the study of arbitrary robotic chains. This thesis studies the problems of forward and inverse kinematics for the Aldebaran NAO humanoid robot. The forward kinematics allow NAO developers to map any configuration of the robot from its own joint space to the three-dimensional physical space, whereas the inverse kinematics provide closed form solutions to finding joint configurations that drive the end effectors of the robot to desired points in the three-dimensional space. The proposed solution was made feasible through a decomposition into five independent problems (head, two arms, two legs), the use of the Denavit-Hartenberg method, and the analytical solution of a non-linear system of equations. The main advantage of the proposed inverse kinematics compared to existing numerical approaches is its accuracy, its efficiency, and the elimination of singularities.

## Getting started with Webots

1. Go to [Webots](https://cyberbotics.com/) website.

2. Install Webots Online

3. Open the Softbank NAO Robot folder and follow the path-
nao-> worlds-> nao_robocup.wbt

4. Run the simulation and click on the robot to make it active.

5. Press arrow keys to move the robot and press 'X' to shoot the ball.

<p align="center">
  <img width="580" height="320" src="/Forward & Inverse Kinematics of the Aldebaran NAO Robot/Webots.jpg">
</p>


## Getting Started with Choregraphe

1. Go to [Choregraphe](https://www.robotlab.com/choregraphe-download) website and register to download the software

2. Install Choregraphe and open the software to start interacting with the NAO robot 

<p align="center">
  <img width="580" height="320" src="/Forward & Inverse Kinematics of the Aldebaran NAO Robot/Choregraphe.jpg">
</p>

