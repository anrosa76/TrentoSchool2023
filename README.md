# TrentoSchool2023

(Step 1) \
Download the LAMMPS (https://www.lammps.org/) trajectory @: https://www.dropbox.com/s/zdk4l6tszfgyegn/trajectory.tar.gz?dl=0 \
The file contains a long trajectory (500x10^6 time steps) of M=10 bead-spring circular (ring) polymer chains, each chain features N=400 monomers.

(Step 2) \
The folder **Tools.tar.gz** contains the following codes (in Fortran90): \
b.1) **dump2xyz_4VMD.f90** - To generate a file which can be read in VMD and visualize the MD trajectory (starting from LAMMPS files). \
b.2) **g1g2g3.f90** - To compute the time mean-square displacements g1, g2, g3 for the polymer molecules. \
b.3) **pRg.f90** - To compute the probability distribution function of the monomer spatial distances from the center of mass of the corresponding polymer chains.
\
\
\
*Bibliography*

**On polymer theory** \
[1] M Rubinstein & RH Colby, *Polymer Physics* (Oxford Univ Press) \
[2] SM Bhattacharjee, *Flory theory for polymers*, Journal of Physics: Condensed Matter (2013) - http://stacks.iop.org/0953-8984/25/i=50/a=503101 \
[3] Zhen-Gang Wang, *50th Anniversary Perspective: Polymer Conformation - A Pedagogical Review*, Macromolecules (2017) - https://doi.org/10.1021/acs.macromol.7b01518 \
\
**On LAMMPS** \
[1] S Plimpton, *Fast Parallel Algorithms for Short-Range Molecular Dynamics*, Journal of Computational Physics (1995) - https://doi.org/10.1006/jcph.1995.1039 \
\
**On ring polymers, branched polymers, etc...** \
[1] M Rubinstein, *Dynamics of Ring Polymers in the Presence of Fixed Obstacles*, Physical Review Letters (1986) - http://link.aps.org/doi/10.1103/PhysRevLett.57.3023 \
[2] A Rosa, R Everaers, *Ring Polymers in the Melt State: The Physics of Crumpling*, Physical Review Letters (2014) - http://link.aps.org/doi/10.1103/PhysRevLett.112.118302 \
[3] A Rosa, R Everaers, *Computer simulations of melts of randomly branching polymers*, The Journal of Chemical Physics (2016) - http://scitation.aip.org/content/aip/journal/jcp/145/16/10.1063/1.4965827 \
[4] R Everaers et al., *Flory theory of randomly branched polymers*, Soft Matter (2017) - http://dx.doi.org/10.1039/C6SM02756C
