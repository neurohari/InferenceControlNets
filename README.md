# InferenceControlNets

This repository contains sample code to show the development of infernce control networks.

## What is included
1. Simulation of posture control task when the arm is perturbed by an external force in the southwest direction.
2. The arm itself is a linear point-mass approximation of human arm, that has been widely used in human behavioral studies [][][].
3. The kinematic plot showing how inactivating the inference node 'e' produces different kinematics compared to inactivating the 'p' nodel in the figure.
3. The wiki page summarizes the mathematical difference between an SOC framework (a linear-quadratic gaussian controller), and the RNNs used in neuroscience community to model motor control tasks.

## What is not included for the inference control networks
1. control on 2Link 6 muscle arm. But such complex biomehcnaics is already emualted with other ANNs in my other repository (XX).
2. Perturbations in random directions. (but even such random perturbations are already simulated for other ANNs in my other repository (XX)).
3. A detailed comparison between different kinematic metrics of experiments[Tomohiko et al., 2021] and simulations using realistic arm model.
