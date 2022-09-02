# RRT* Path Planning and Trajectory Optimization for a Quadrotor
## MIT Underactuated Robotics (6.832) Final Project
Portia Gaitskell '23 and Christian Viteri '23

Quadrotor manipulation through cluttered environ- ments requires efficient evaluation of safe regions and reliable control. This project presents our methods for combining sample based planning methods with trajectory optimization to find the optimal trajectory for a quadrotor through an obstacle field. We used RRT* to find a path between a start and end point given the preset obstacles. The path was then used as an initial guess in a direct collocation trajectory optimization in Drake with collision avoidance constraints to find the optimal trajectory through space. The dynamics were stabilized by a time-varying finite horizon linear quadratic regulator. The optimization problem successfully avoids spherical and rectangular obstacles in space and is stabilized by finite-horizon LQR in response to random perturbations.

Full project presentation video: https://www.youtube.com/watch?v=lUO88Udkokw&t=3s

**Github is still under progress**
