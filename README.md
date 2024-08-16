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
2) Model Predictive Control (MPC)
   
In the first control startegy we use PID for longitudinal Controller and Pure Pursuit as lateral control as Follows 
![image](https://github.com/user-attachments/assets/0e7ffb6b-4772-40e1-af5c-0346821ccef1)



## 1 . Pure Pursuit Control

![image](https://github.com/user-attachments/assets/71fc4594-93b8-4e15-bf7f-1b2fa6210555)


![image](https://github.com/user-attachments/assets/94c646bb-3699-40fe-9415-c21d6a307f0e)

