# N-Body-Simulation

This is a code repository for a basic N-Body simulation. It is written in Python and utilizes the Leapfrog integration method to simulate the motion of particles in 3Dspace.
Requirements

- Python 3.6+
- Matplotlib
- Numpy
- Numba
- Json
    
## Function Description

'Run_sim(N_steps, pos_arr, mom_arr, mass_arr, start=0, dt=1.e-2, G=6.67408e-11, epsilon=0.01)'

This function runs the simulation and returns the following:
    'pos_arr':  An array containing the positions of the particles after the simulation.
    mom_arr: An array containing the momenta of the particles after the simulation.
    pos_data: An array containing the positions of the particles at each step of the simulation.

Parameters

    N_steps: The number of steps in the simulation.
    pos_arr: An array containing the initial positions of the particles.
    mom_arr: An array containing the initial momenta of the particles.
    mass_arr: An array containing the masses of the particles.
    start (optional): The starting step of the simulation. Default is 0.
    dt (optional): The time step of the simulation. Default is 1.e-2.
    G (optional): The gravitational constant. Default is 6.67408e-11.
    epsilon (optional): The softening parameter. Default is 0.01.

Usage

    Import the Run_sim function from nbody_sim.py.
    Provide the necessary inputs: N_steps, pos_arr, mom_arr, and mass_arr.
    Optional parameters such as start, dt, G, and epsilon can be modified to suit the needs of the simulation.
    Call the function Run_sim(N_steps, pos_arr, mom_arr, mass_arr, start=0, dt=1.e-2, G=6.67408e-11, epsilon=0.01).
