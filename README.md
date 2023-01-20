# TrentoSchool2023

**(Step 1)**
* Download the LAMMPS (https://www.lammps.org/) trajectory @: https://www.dropbox.com/s/zdk4l6tszfgyegn/trajectory.tar.gz?dl=0
* The file contains a long trajectory (500x10^6 time steps) of M=10 bead-spring circular (ring) polymer chains, each chain features N=400 monomers.

**(Step 2)** \
The folder **Tools.tar.gz** contains the following codes (in Fortran90):
* **dump2xyz_4VMD.f90** - To generate a file which can be read in VMD and visualize the MD trajectory (starting from LAMMPS files).
* **g1g2g3.f90** - To compute the time mean-square displacements g1, g2, g3 for the polymer molecules.
* **pRg.f90** - To compute the probability distribution function of the monomer spatial distances from the center of mass of the corresponding polymer chains.

NOTE: The file **vmdscene.png** features a single snapshot of the trajectory.

\
*Bibliography*

**On polymer theory**
* M Rubinstein & RH Colby, *Polymer physics* (Oxford Univ Press)
* SM Bhattacharjee et al., *Flory theory for polymers*, Journal of Physics: Condensed Matter (2013) - http://stacks.iop.org/0953-8984/25/i=50/a=503101 
* Zhen-Gang Wang, *50th anniversary perspective: polymer conformation - A pedagogical review*, Macromolecules (2017) - https://doi.org/10.1021/acs.macromol.7b01518

**On LAMMPS**
* S Plimpton, *Fast parallel algorithms for short-range molecular dynamics*, Journal of Computational Physics (1995) - https://doi.org/10.1006/jcph.1995.1039
* Official website: https://www.lammps.org/

**On ring polymers, branched polymers, etc...**
* M Rubinstein, *Dynamics of ring polymers in the presence of fixed obstacles*, Physical Review Letters (1986) - http://link.aps.org/doi/10.1103/PhysRevLett.57.3023
* A Rosa, R Everaers, *Ring polymers in the melt state: The physics of crumpling*, Physical Review Letters (2014) - http://link.aps.org/doi/10.1103/PhysRevLett.112.118302
* A Rosa, R Everaers, *Computer simulations of melts of randomly branching polymers*, The Journal of Chemical Physics (2016) - http://scitation.aip.org/content/aip/journal/jcp/145/16/10.1063/1.4965827
* R Everaers et al., *Flory theory of randomly branched polymers*, Soft Matter (2017) - http://dx.doi.org/10.1039/C6SM02756C

**On topologically-constrained polymers & chromatin organization**
* A Grosberg et al., *Crumpled globule model of the three-dimensional structure of DNA*, EPL (Europhysics Letters) (1993) - http://stacks.iop.org/0295-5075/23/i=5/a=012
* A Rosa & R Everaers, *Structure and dynamics of interphase chromosomes*, PLOS Computational Biology (2008) - https://doi.org/10.1371/journal.pcbi.1000153
* JD Halverson et al., *From a melt of rings to chromosome territories: The role of topological constraints in genome folding*, Reports on Progress in Physics (2014) - http://stacks.iop.org/0034-4885/77/i=2/a=022601
* LA Mirny, *The Fractal Globule as a Model of Chromatin Architecture in the Cell*, Chromosome Research (2011) - https://doi.org/10.1007/s10577-010-9177-0 

**On chromosome territories, topological domains, Hi-C, chromatin mechanics, etc...**
* T Cremer & C Cremer, *Rise, fall and resurrection of chromosome territories: A historical perspective. Part I,II,III*, European Journal of Histochemistry (2006) - https://www.ejh.it/index.php/ejh/article/view/989/1110
* E Lieberman-Aiden et al., *Comprehensive mapping of long-range interactions reveals folding principles of the human genome*, Science (2009) - https://doi.org/10.1126/science.1181369
* JR Dixon et al., *Topological domains in mammalian genomes identified by analysis of chromatin interactions*, Nature (2012) - http://dx.doi.org/10.1038/nature11082
* VIP Keizer et al., *Live-cell micromanipulation of a genomic locus reveals interphase chromatin mechanics*, Science (2022) - https://doi.org/10.1126/science.abi9810
