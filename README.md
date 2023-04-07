# N-body Simulation

This is a code repository for a basic N-body simulation. 

It is written in Python and utilizes the Leapfrog integration method to simulate the motion of particles in 3D space.

## Requirements

* Python 3.6+
* Matplotlib
* Numpy
* Numba
* Json

## Function Description

`Run_sim(N_steps, pos_arr, mom_arr, mass_arr, start=0, dt=1.e-2, G=6.67408e-11, epsilon=0.01)`

### Output

This function runs the simulation and returns the following:

* `pos_arr`: An array containing the positions of the particles after the simulation.
* `mom_arr`: An array containing the momenta of the particles after the simulation.  
* `pos_data`: An array containing the positions of the particles at each step of the simulation.

### Input Parameters

    N_steps : int
        The number of steps in the simulation.
    pos_arr : numpy array
        An array containing the initial positions of the particles.
    mom_arr : numpy array
        An array containing the initial momenta of the particles.
    mass_arr : numpy array
        An array containing the masses of the particles.
    start : int, optional
        The starting step of the simulation. Default is 0.
    dt : float, optional
        The time step of the simulation. Default is 1.e-2.
    G : float, optional
        The gravitational constant. Default is 6.67408e-11.
    epsilon : float, optional
        The softening parameter. Default is 0.01.

### Usage

* Execute the imports cell.
* Execute the `Run_sim` function definition in brute_force.ipynb .
* Provide the necessary inputs: N_steps, pos_arr, mom_arr, and mass_arr.
* Optional parameters such as start, dt, G, and epsilon can be modified to suit the needs of the simulation.
* Call the function Run_sim(N_steps, pos_arr, mom_arr, mass_arr, start=0, dt=1.e-2, G=6.67408e-11, epsilon=0.01) by assigning to a varialbe.
* Unpack the variable to get the `pos_arr`, `mom_arr`, `pos_data`.

## Simulation video

* I have ran the simulation with 20000 parrticles in the mass range between 0.3 to 2.23 Solar Mass for a time period of 300 Myrs. 
* The data from the runs were collected and animated into a video. 
* The video runs at a rate of 1 Myr per sec. 
* The video can befound [here](https://www.youtube.com/watch?v=hIO0DGP90Xg) 

![Picture](https://github.com/Balaji-0-5/N-Body-Simulation/blob/360c513accb6df68e839c8c7968f62e94aea894c/Project/Initial_config.png)
