# TrentoSchool2023

*(Step 1)* \
Download the LAMMPS (https://www.lammps.org/) trajectory @: https://www.dropbox.com/s/zdk4l6tszfgyegn/trajectory.tar.gz?dl=0 \
The file contains a long trajectory (500x10^6 time steps) of M=10 bead-spring circular (ring) polymer chains, each chain features N=400 monomers.

*(Step 2)* \
The folder **Tools.tar.gz** contains the following codes (in Fortran90): \
b.1) **dump2xyz_4VMD.f90** - To generate a file which can be read in VMD and visualize the MD trajectory (starting from LAMMPS files). \
b.2) **g1g2g3.f90** - To compute the time mean-square displacements g1, g2, g3 for the polymer molecules. \
b.3) **pRg.f90** - To compute the probability distribution function of the monomer spatial distances from the center of mass of the corresponding polymer chains.
\
\
NOTE: The file **vmdscene.png** features a single snapshot of the trajectory.
\
\
\
*Bibliography*

**On polymer theory** \
[1] M Rubinstein & RH Colby, *Polymer Physics* (Oxford Univ Press) \
[2] SM Bhattacharjee et al., *Flory theory for polymers*, Journal of Physics: Condensed Matter (2013) - http://stacks.iop.org/0953-8984/25/i=50/a=503101 \
[3] Zhen-Gang Wang, *50th Anniversary Perspective: Polymer Conformation - A Pedagogical Review*, Macromolecules (2017) - https://doi.org/10.1021/acs.macromol.7b01518 \
\
**On LAMMPS** \
[4] S Plimpton, *Fast Parallel Algorithms for Short-Range Molecular Dynamics*, Journal of Computational Physics (1995) - https://doi.org/10.1006/jcph.1995.1039 \
\
**On ring polymers, branched polymers, etc...** \
[5] M Rubinstein, *Dynamics of Ring Polymers in the Presence of Fixed Obstacles*, Physical Review Letters (1986) - http://link.aps.org/doi/10.1103/PhysRevLett.57.3023 \
[6] A Rosa, R Everaers, *Ring Polymers in the Melt State: The Physics of Crumpling*, Physical Review Letters (2014) - http://link.aps.org/doi/10.1103/PhysRevLett.112.118302 \
[7] A Rosa, R Everaers, *Computer Simulations of Melts of Randomly Branching Polymers*, The Journal of Chemical Physics (2016) - http://scitation.aip.org/content/aip/journal/jcp/145/16/10.1063/1.4965827 \
[8] R Everaers et al., *Flory Theory of Randomly Branched Polymers*, Soft Matter (2017) - http://dx.doi.org/10.1039/C6SM02756C \
\
**On topologically-constrained polymers & chromatin organization** \
[9] A Grosberg et al., *Crumpled Globule Model of the Three-Dimensional Structure of DNA*, EPL (Europhysics Letters) (1993) - http://stacks.iop.org/0295-5075/23/i=5/a=012 \
[10] A Rosa & R Everaers, *Structure and Dynamics of Interphase Chromosomes*, PLOS Computational Biology (2008) - https://doi.org/10.1371/journal.pcbi.1000153 \
[11] JD Halverson et al., *From a Melt of Rings to Chromosome Territories: The Role of Topological Constraints in Genome Folding*, Reports on Progress in Physics (2014) - http://stacks.iop.org/0034-4885/77/i=2/a=022601 \
[12] LA Mirny, *The Fractal Globule as a Model of Chromatin Architecture in the Cell*, Chromosome Research (2011) - https://doi.org/10.1007/s10577-010-9177-0 \
\
**On chromosome territories, topological domains, Hi-C, chromatin mechanics, etc...** \
[13] T Cremer & C Cremer, *Rise, Fall and Resurrection of Chromosome Territories: A Historical Perspective. Part I,II,III*, EUROPEAN JOURNAL OF HISTOCHEMISTRY (2006) - https://www.ejh.it/index.php/ejh/article/view/989/1110 \
[14] E Lieberman-Aiden et al., *Comprehensive Mapping of Long-Range Interactions Reveals Folding Principles of the Human Genome*, Science (2009) - https://doi.org/10.1126/science.1181369 \
[15] JR Dixon et al., *Topological Domains in Mammalian Genomes identified by Analysis of Chromatin Interactions*, Nature (2012) - http://dx.doi.org/10.1038/nature11082 \
[16] VIP Keizer et al., *Live-cell Micromanipulation of a Genomic Locus reveals Interphase Chromatin Mechanics*, Science (2022) - https://doi.org/10.1126/science.abi9810
