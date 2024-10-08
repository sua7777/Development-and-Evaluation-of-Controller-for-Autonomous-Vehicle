# Developement and Evaluation of Controller for Autonomous Driving

## Objective :
The objective of this thesis work is to develope a controller for robust trajectory tracking and control of autonomous vehicle. The performance of the control algorithms is evaluated using CARLA virtual simulator. 

![top_view](https://github.com/user-attachments/assets/1620282e-b94b-4d83-9f58-677aa876b3cd)


Longitudinal Control:
> Responsible for managing the vehicle's speed, acceleration / deceleration.
> Control of the vehicle's motion along its longitudinal axis.
> Controls brake and throttle command to achieve the desired longitudinal motion.

Lateral Control :
> Control of the vehicle's motion along its lateral axis.
> Considers lateral dynamics of car.
> Steering angle and orientation (heading) are the controlled variables.

We have designed two control strategies namely, 
1) PID + Pure Pursuit Control
   > In the first control startegy we use PID for longitudinal Controller and Pure Pursuit as lateral control.
   
3) Model Predictive Control (MPC)
   


## 1 . Pure Pursuit Control (PPC)  :          [Result]: https://youtu.be/hC2OsCH2b6E


Pure Pursuit is a geometrical type controller. Its working is based purely on geometry.

![image](https://github.com/user-attachments/assets/5eb3e452-a6f8-408f-8533-dadbb9538d67)



## 2. Model Predictive Control (MPC):         [Result]: https://youtu.be/PDJeTByIZtc

Non-linear optimization method was used for MPC. 

![image](https://github.com/user-attachments/assets/29867def-899f-4f80-a132-525b466db679)


![image](https://github.com/user-attachments/assets/b054d1d7-880d-44a0-b2b0-f31474c2306c)

![image](https://github.com/user-attachments/assets/6311db15-8ffc-4143-a8a8-415a86d33b60)








