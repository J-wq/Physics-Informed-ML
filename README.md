# Physics-Informed-ML
The repository provides a tutorial for the implementation of a physics informed neural network (PINN) to solve a continous heat conduction problem for a cube at an applied heat source on the surface. The PINN can be used to model the temperature fields within materials exposed to, e.g. laser irradiation in additive manufacturing. 

## Underlying physics
The underlying solved partial differential equation is the heat conduction: 

\begin{equation}
  $\frac{d}{dt}u$
\end{equation}


## Modeled domain


## Results
The temperature field at t=0.5 along the cross section of the laser path can be seen. The heat conduction show an expected behavior and the quantitive error is approximaty 4% in comparision to FEM solutions. 

![alt text](https://github.com/J-wq/Physics-Informed-ML/blob/main/Images/PINN_simulation_cross_section.png?raw=true)


## Citing this repository
Please cite the publication when using the repository:
- Voigt and Moeckel, 'Physic informed neural networks for heat conduction modeling in material processing and production'

