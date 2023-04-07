# N-Body-Simulation

This is a code repository for a basic N-Body simulation. It is written in Python and utilizes the Leapfrog integration method.
Requirements

- Python 3.6+
- Matplotlib
- Numpy
- Numba
- Json
    
Usage

To run the simulation, execute the Run_sim function file in the terminal:

css

python main.py

The simulation parameters (such as number of particles, time step, and total time) can be adjusted in the config.py file.

The initial conditions of the particles can be set in the init_particles() function in the particles.py file.
Output

The simulation outputs an animated plot of the particle trajectories, as well as a static plot of the final particle positions.
Credits

This simulation was developed by [Your Name Here]. It is based on the Leapfrog integration method described in "Numerical Methods in Astrophysics: An Introduction" by Peter Bodenheimer, Gregory P. Laughlin, and Michal Rozyczka.
License

This project is licensed under the MIT License. See the LICENSE file for more information.
