# A Model Predictive Control Based Autopilot for Aircraft

## Description

This project, submitted for my Bachelor's degree in Mechanical Engineering at Trinity College Dublin, explores the implementation of a Model Predictive Controller (MPC) based autopilot for aircraft. Written entirely in Simulink and MATLAB, this project deepened my understanding of modern control systems, specifically MPC.

The reference trajetory ($x_{pos}, y_{pos}, z_{pos}$) was generated using "FlightGear" the flight simulator and the aircraft model was sourced from Cook's "Flight Dynamics Principles" [1].

The results of my project indicate that MPC has potential as a control strategy for aircraft, provided that the flight path is not overly aggressive. The following plots demonstrate this capability.

| ![Altitude](https://raw.githubusercontent.com/keatinl1/MPC-Final-Year-Project/main/Figures/double%20alt.jpg) | ![Lateral](https://raw.githubusercontent.com/keatinl1/MPC-Final-Year-Project/main/Figures/double%20lat.jpg) |
|:--:|:--:|
| *Altitude* | *Lateral* |

| ![Aggressive Altitude](https://raw.githubusercontent.com/keatinl1/MPC-Final-Year-Project/main/Figures/double%20aggressive%20alt.jpg) | ![Aggressive Lateral](https://raw.githubusercontent.com/keatinl1/MPC-Final-Year-Project/main/Figures/double%20aggressive%20lat.jpg) |
|:--:|:--:|
| *Aggressive Altitude* | *Aggressive Lateral* |



## Getting Started

### Dependencies
Windows 10 (or greater)\
MATLAB R2021b (or greater)\
Simulink

### Installing
Download the project files from [here](https://github.com/keatinl1/MPC-Final-Year-Project).\
Download the MPC toolbox from the MATLAB library explorer, [link](https://www.mathworks.com/products/model-predictive-control.html).\
Download the aerospace toolbox from the matlab library explorer, [link](https://www.mathworks.com/products/aerospace-toolbox.html).


### Executing program

1 - Open MATLAB and clear your workspace with the command ```clear all```

2 - Run the command ```data.mat``` to load the reference trajectory

3 - Open Simulation.slx in Simulink

4 - Click the green run arrow

The results are exported to your MATLAB workspace automatically.

You can view the simulation output by clicking the "scopes" in the 
Simulink file, or through the workspace i.e. plotting the vectors out.sim_alt, out.sim_lat


## License

This project is licensed under the GNU General Public License (GPL) 3.0 License - see the LICENSE.md file for details

## References

[1] Cook, M.V.. (2013). Flight Dynamics Principles. 10.1016/2010-0-65889-5.
