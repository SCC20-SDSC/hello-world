[1] Compile:

module purge
module load openmpi/4.0.4

mpif90 -o hello_mpi hello_mpi.f90

[2] Run:

sbatch hellompi-slurm.sb

NOTE: for other compilers, replace "gcc"
with the one you want to use.
