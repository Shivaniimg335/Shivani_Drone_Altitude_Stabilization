# Shivani_Drone_Altitude_Stabilization
This project proves the efficacy of PID control for UAV applications. By balancing proportional power, integral correction, and derivative damping, the system achieves stable and responsive flight, meeting all key performance and stability criteria.
Drone Altitude Stabilization using PID Control:
*Overview
This project implements a drone altitude stabilization system using PID control in MATLAB and Simulink. The drone dynamics are modeled using the transfer function:
G(s)=1/s^2+2s+5
The objective is to maintain stable drone altitude while minimizing overshoot, reducing settling time, and rejecting external disturbances such as wind.

*Objectives
Analyze open-loop response
Design a PID controller
Simulate closed-loop response
Introduce wind disturbance and evaluate robustness

*Tools Used
MATLAB
Simulink
Control System Toolbox

*Controller Parameters
Kp = 40
Ki = 25
Kd = 12
Performance Achieved
Overshoot < 10%
Settling Time < 3 seconds
Near-zero steady-state error
Stable operation under disturbance

*System Analysis
The open-loop system showed higher overshoot and slower settling time. A PID controller was implemented to improve transient and steady-state performance. Root locus, pole-zero maps, and step response analysis were used to evaluate stability.

*Disturbance Analysis
A wind disturbance of magnitude 0.2 was introduced at 5 seconds. The PID controller successfully rejected the disturbance and maintained stable altitude.

*Files Included
MATLAB scripts
Simulink model
Step response plots
Root locus plots
Disturbance response analysis

*Applications
Drone altitude stabilization
UAV control systems
Aerospace control
Feedback control system design

*Conclusion
The designed PID controller successfully stabilized the drone altitude and satisfied all control objectives, including low overshoot, fast settling time, near-zero steady-state error, and robustness against external disturbances.
