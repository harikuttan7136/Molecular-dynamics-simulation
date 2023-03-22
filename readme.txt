NVE Simulation for the set of atoms using LJ potential whose position and species is given using velocity-verlet integration approach
LJ_A80B20_3D_100_species.npy contains the type of particles
LJ_A80B20_3D_100_pos.npy contains the position of particles

The system has two types of particles with composition A80B20 consisting of total N=100 particles in
a cubic ensemble of size 4.3679 with periodic boundaries. The interaction between the particles is
governed by LJ potential. The LJ parameters are
εAA = 1.0, εAB = 1.5, εBB = 0.5, σAA = 1.0, σAB = 0.8 and σBB = 0.88. The mass for all particles is set to
1.0. The interaction cutoff, rc = 2.5σ and the time step dt = 0.003.
Use following command to load the configuration as numpy arrays
positions=numpy.load(“LJ_A80B20_3D_100_pos.npy”)
species =numpy.load(“LJ_A80B20_3D_100_species.npy”)
positions : An array of shape (100,3) containing coordinates of particles
species : An array of shape (100,) containing atom type (‘0’ for A and ‘1’ for B )
The simulation box is a cube with sides along cartesian axes and length equal 4.3679 starting from
origin.
