### Hi there 👋

I'm an [EPSRC research fellow](https://epsrc.ukri.org/about/people/michaelfaulkner/) at the [University of Bristol](https://research-information.bristol.ac.uk/en/persons/michael-faulkner(76c7604a-6db1-4d4f-948e-db5a1f7afc2b).html).  Primarily, I’m a computational statistical physicist, which means that I use statistics and simulation algorithms to model many particles interacting with one another in a single system.  I specialise in molecular simulation in soft-matter physics, Markovian Monte Carlo algorithms in statistical physics and Bayesian computation, and the theory and simulation of two-dimensional electrolytes, magnets and superconductors.

For more details, here's [my personal website](https://michaelfaulkner.github.io) and [Bristol webpage](https://research-information.bris.ac.uk/en/persons/michael-faulkner).  And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my publications and grants.

## 👨‍🔧  Main contributions on Github 
- An original co-author of [super-aLby](https://github.com/michaelfaulkner/super-aLby) (a Python application for super-relativistic Monte Carlo simulation in soft-matter physics and Bayesian computation).
- An original co-author of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) (a hybrid Python-C application for event-chain Monte Carlo simulation in soft-matter physics).
- The sole author of [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) (a hybrid Fortran-Python application for Metropolis and event-chain Monte Carlo simulation of two-dimensional XY models and the two-dimensional lattice-field electrolyte).

## 🔑 Key scientific achievements
- We discovered [the ergodicity-breaking mechanism](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of the Berezinskii-Kosterlitz-Thouless phase transition in the two-dimensional lattice-field electrolyte.  We then presented an [electric-field representation of the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) of planar magnets, superfluids and superconductors, which demonstrated that this corresponds to an ergodic freezing of global-twist excitations in the phase of the magnetisation / condensate wavefunction.
- We designed [an event-chain algorithm](https://doi.org/10.1063/1.5036638) for the simulation of molecular models in soft-matter physics (e.g., the SPC/Fw all-atom model of water).  This is the only molecular simulation algorithm with a finite mixing time (the time to reach equilibrium from a random initial configuration) and is the basis of our hybrid Python-C application [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh), which we set out in detail [here](https://doi.org/10.1016/j.cpc.2020.107168).
- We designed [super-relativistic Monte Carlo](https://doi.org/10.1093/biomet/asz013) for the simulation of probability models in Bayesian computation (set out in details in section 5.2 of [the linked paper](https://doi.org/10.1093/biomet/asz013)).  By (relativistically) slowing down the Newtonian dynamics in high-gradient regions of probability space, this new simulation algorithm circumvents the numerical instabilities of Hamiltonian Monte Carlo when applied to light-tailed probability distributions.  It is the basis of our Python application [super-aLby](https://github.com/michaelfaulkner/super-aLby).

## 🔭  Current research
- I’m currently using [my model](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of ergodicity breaking in the two-dimensional electrolyte in order to explain [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in lanthanum strontium copper oxide.  This is made possible by the [emergent electrostatics in the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) of planar mangets, superfluids and superconductors.  The project uses [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the model system.
- With collegues in computational statistics, I’m also writing a guide to statistical physics for the statistician.  This will be useful because there's a lot of overlap between the two fields, but cross-pollination of knowledge is currently slow due to poor understanding within each discipline of the goals and nomenclature of the other field.  This project uses [super-aLby](https://github.com/michaelfaulkner/super-aLby) and [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the models presented.

## 🌱  Future plans
- Emergent physical dynamics in Metropolis Monte Carlo algorithms.
- Application of ideas from Bayesian computation to fix some fundamental convergence issues in [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh).
- Further projects on emergent electrostatics in two-dimensional XY models.

## 📫  Contact
- Email me at michael.faulkner AT bristol.ac.uk
- As outlined above, you can find more details on [my personal website](https://michaelfaulkner.github.io) and [Bristol webpage](https://research-information.bris.ac.uk/en/persons/michael-faulkner).
- And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my publications and grants.
