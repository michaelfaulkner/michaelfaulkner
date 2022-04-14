### Hi there 👋

I'm an [EPSRC research fellow](https://epsrc.ukri.org/about/people/michaelfaulkner/) at the [University of Bristol](https://research-information.bristol.ac.uk/en/persons/michael-faulkner(76c7604a-6db1-4d4f-948e-db5a1f7afc2b).html).  Primarily, I’m a computational statistical physicist, which means that I use statistics and simulation algorithms to model large numbers of particles interacting with each another in a single material.  I specialise in:
- Theory and simulation of two-dimensional electrolytes, magnets, superfluids and superconductors.
- Molecular simulation in soft-matter physics, with a focus on high precision and numerical stability.
- Markovian Monte Carlo algorithms in statistical physics and Bayesian computation.

Previously, I was a doctoral researcher at [University College London](https://www.ucl.ac.uk/condensed-matter-material-physics/) and [Ecole normale supérieure de Lyon](http://www.ens-lyon.fr/PHYSIQUE/teams/physique-theorique/research-topics/statistical-physics), under the co-supervision of [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique).  After a short postdoc and then a teaching position in the School of Mathematics at Bristol, I moved to the School of Physics to start my EPSRC fellowship in August 2017.

I was also a visiting scientist at [Ecole normale supérieure](http://www.phys.ens.fr/?lang=fr) from September 2017 to October 2018, and won a Max Planck Institute fellowship to visit the [Max Planck Institute for the Physics of Complex Systems](https://www.pks.mpg.de) in Dresden in April 2018.

For more details, visit [my personal website](https://michaelfaulkner.github.io).  And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my publications and grants.

## 👨‍🔧  Main contributions to Github 
- An original co-author of [super-aLby](https://github.com/michaelfaulkner/super-aLby) — a Python application for super-relativistic Monte Carlo simulation in soft-matter physics and Bayesian computation.
- An original co-author of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) — a hybrid Python-C application for event-chain Monte Carlo simulation in soft-matter physics.
- The sole author of [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) — a hybrid Fortran-Python application for Metropolis and event-chain Monte Carlo simulation of two-dimensional XY models and the two-dimensional lattice-field electrolyte.

## 🔑 Key scientific achievements
- Discovered a general symmetry breaking at the Berezinskii-Kosterlitz-Thouless phase transition.  This resolved the paradox of a predicted absence of spontaneous symmetry breaking despite observations of symmetry-breaking phenomena on experimental timescales in many 2D systems, such as the [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in lanthanum strontium copper oxide.  My results provided a model for symmetry-restoring timescales in a wide array of experimental systems.
- Defined the above new concept - general symmetry breaking - which encompasses both spontaneous symmetry breaking and the experimental anomalies.
- Discovered (with [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique)) [the ergodicity-breaking mechanism](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of the Berezinskii-Kosterlitz-Thouless phase transition.  This was cited as a possible explanation for [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in lanthanum strontium copper oxide and proved to induce the above general symmetry breaking that explains the correlated fluctuations.
- Developed the grand-canonical analogue of the [Maggs lattice-field model of electrostatics](https://doi.org/10.1103/PhysRevLett.88.196402) and showed its equivalence to [the Villain model](https://doi.org/10.1051/jphys:01975003606058100) of planar magnets (see Section II and Appendix B of [the ergodicity paper](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412)).  We then presented an [electric-field representation of the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) — a more realistic model of planar magnets, superfluids and superconductors — which mapped the ergodicity breaking to the ergodic exclusion of global phase twists in the magnetic spins / condensate wavefunction.
- Designed (with [Liang Qin](https://scholar.google.com/citations?user=rGW6nKUAAAAJ), [Tony Maggs](https://turner.pct.espci.fr/~amaggs/index2.html) and [Werner Krauth](http://www.lps.ens.fr/~krauth/index.php/Main_Page)) [an event-chain algorithm](https://doi.org/10.1063/1.5036638) for numerically stable all-atom molecular simulation in soft-matter physics.  This is the only molecular simulation algorithm that mixes (equilibrates from a random initial configuration) Coulomb-based models in O[N log(N)] computations, where N is the number of particles.  It also achieves machine precision and is the basis of our hybrid Python-C application [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh), which we set out in detail [here](https://doi.org/10.1016/j.cpc.2020.107168).
- Designed (with statisticians [Sam Livingstone](https://www.ucl.ac.uk/statistics/department-information/staff/dr-samuel-livingstone) and [Gareth Roberts](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/roberts/)) [super-relativistic Monte Carlo](https://doi.org/10.1093/biomet/asz013) for high-stability simulation of probability models in Bayesian computation (see section 5.2 of [the linked paper](https://doi.org/10.1093/biomet/asz013) for details).  By slowing down the Newtonian dynamics in high-gradient regions of probability space, this new simulation algorithm circumvents the numerical instabilities of Hamiltonian Monte Carlo when applied to light-tailed probability distributions.  It also achieves machine precision and is the basis of our Python application [super-aLby](https://github.com/michaelfaulkner/super-aLby).

## 🔭  Current research
- I’m currently using [my model](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of ergodicity breaking in the two-dimensional electrolyte to explain [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in lanthanum strontium copper oxide.  This is made possible by [emergent electrostatics in the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) of planar mangets, superfluids and superconductors.  The project uses [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the model system.
- This has already resulted in the general symmetry breaking outlined above.  The next part of the puzzle is a model for the correlated dynamics that are closely connected to the loss of symmetry.
- [Sam Livingstone](https://www.ucl.ac.uk/statistics/department-information/staff/dr-samuel-livingstone) and I are writing a guide to statistical physics for the statistician.  This will be useful because there's a lot of overlap between the two fields, but cross-pollination of knowledge is currently slow due to poor understanding within each discipline of the goals and nomenclature of the other field.  This project uses [super-aLby](https://github.com/michaelfaulkner/super-aLby) and [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the models presented.
- We are also working on super-relativistic Monte Carlo in soft-matter physics, using [super-aLby](https://github.com/michaelfaulkner/super-aLby).

## 🌱  Future plans
- Emergent physical dynamics in Metropolis Monte Carlo algorithms.
- Event-chain dynamics in a critical system.
- Application of ideas from Bayesian computation to fix some fundamental convergence issues in [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh).
- Further projects on emergent electrostatics in two-dimensional XY models.

## 📫  Contact
- Email me at michael.faulkner AT bristol.ac.uk
- As outlined above, you can find more details on [my personal website](https://michaelfaulkner.github.io) and [Bristol webpage](https://research-information.bris.ac.uk/en/persons/michael-faulkner).
- And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my publications and grants.
