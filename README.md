## 👋 About me

I'm an [EPSRC research fellow](https://epsrc.ukri.org/about/people/michaelfaulkner/) at the [University of Bristol](https://research-information.bristol.ac.uk/en/persons/michael-faulkner(76c7604a-6db1-4d4f-948e-db5a1f7afc2b).html).  Primarily, I’m a computational statistical physicist, which means that I use statistics and simulation algorithms to model large numbers of particles interacting with each another in a single material.  I specialise in:
- Theory and simulation of planar Coulomb fluids, magnets, superfluids and superconductors.
- Molecular simulation in soft-matter physics, with a focus on Coulomb fluids, high precision and numerical stability.
- Monte Carlo sampling algorithms in statistical physics and Bayesian computational statistics.

Previously, I was a doctoral researcher at [University College London](https://www.ucl.ac.uk/condensed-matter-material-physics/) and [Ecole normale supérieure de Lyon](http://www.ens-lyon.fr/PHYSIQUE/teams/physique-theorique/research-topics/statistical-physics), under the co-supervision of [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique).  After a short postdoc and then a teaching position at Bristol Maths, I moved to Bristol Physics to start my EPSRC fellowship in August 2017.

I was also a visiting scientist at [Ecole normale supérieure](http://www.phys.ens.fr/?lang=fr) from September 2017 to October 2018, and won a Max Planck Institute fellowship to visit the [Max Planck Institute for the Physics of Complex Systems](https://www.pks.mpg.de) in Dresden in April 2018.

For more details, visit [my personal website](https://michaelfaulkner.github.io).  And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my [publications](https://github.com/michaelfaulkner#--academic-publications) and grants.

## 👨‍🔧  Main contributions to Github 
- An original co-author of [super-aLby](https://github.com/michaelfaulkner/super-aLby) — a mediator-based Python application for super-relativistic, Hamiltonian, Metropolis and Wolff Monte Carlo in statistical physics and Bayesian computation.
- An original co-author of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) — a mediator-based Python-C application for atomistic event chain Monte Carlo simulation in soft matter.
- The sole author of [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) — a Fortran-Python application for Metropolis and event chain Monte Carlo simulation of 2DXY models and the 2D lattice-field electrolyte.

## 🔑 Key scientific achievements
### Thin films
- Discovered general symmetry breaking at the Berezinskii-Kosterlitz-Thouless (BKT) transition.  This resolved the paradox of symmetry-breaking phenomena observed on experimental timescales in many 2D systems, despite a predicted absence of spontaneous symmetry breaking.  Examples include [superconducting films of lanthanum strontium copper oxide (LSCO)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503).  The result provides a model for symmetry-restoring (or memory) timescales in a wide array of experimental systems.
- Defined the above new concept — general symmetry breaking — which encompasses both spontaneous symmetry breaking and the experimental anomalies.
- Discovered (with [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique)) [the ergodicity-breaking mechanism](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) of the BKT transition, in the 2D lattice-field Coulomb fluid.  This was cited as a possible explanation for [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in the LSCO film and proved to induce the above general symmetry breaking.
- Developed the grand-canonical analogue of the [Maggs lattice-field model of electrostatics](https://doi.org/10.1103/PhysRevLett.88.196402) and showed its equivalence to [the Villain model](https://doi.org/10.1051/jphys:01975003606058100) of planar magnets (see Section II and Appendix B of [the ergodicity paper](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412)).  We then presented an [electric-field representation of the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) — a more realistic model of planar magnets, superfluids and superconductors — which mapped the ergodicity breaking to the ergodic exclusion of global phase twists in the magnetic spins / condensate wavefunction.
### Molecular simulation and event chain Monte Carlo
- Designed (with [Liang Qin](https://scholar.google.com/citations?user=rGW6nKUAAAAJ), [Tony Maggs](https://turner.pct.espci.fr/~amaggs/index2.html) and [Werner Krauth](http://www.lps.ens.fr/~krauth/index.php/Main_Page)) [an event-chain algorithm](https://doi.org/10.1063/1.5036638) for numerically stable all-atom molecular Coulomb simulations in soft matter.  This is the only molecular simulation algorithm that mixes (equilibrates from a random initial configuration) Coulomb-based models in *O(N log(N))* computations, where *N* is the number of particles.  It also achieves machine precision and is the basis of...
- ...our mediator-based Python-C application [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh), which we set out in detail [here](https://doi.org/10.1016/j.cpc.2020.107168).
### Sampling algorithms and interface with (Bayesian) computational statistics
- Presented (with statistician [Sam Livingstone](https://www.ucl.ac.uk/statistics/department-information/staff/dr-samuel-livingstone)) an [in-depth review of statistical physics and its sampling algorithms](https://arxiv.org/abs/2208.04751), but in the language of statistics and machine learning.  This will accelerate innovation and cross-pollination of knowledge between the two fields, by strengthening understanding within each discipline of the goals and nomenclature of the other field.  This project uses [super-aLby](https://github.com/michaelfaulkner/super-aLby) and [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the models presented.  We are now building on the connections presented in the paper.
- Designed (with statisticians [Sam Livingstone](https://www.ucl.ac.uk/statistics/department-information/staff/dr-samuel-livingstone) and [Gareth Roberts](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/roberts/)) [super-relativistic Monte Carlo](https://doi.org/10.1093/biomet/asz013) for high-stability simulation of probability models in Bayesian computation (see section 5.2 of [the linked paper](https://doi.org/10.1093/biomet/asz013) for details).  By slowing down the Newtonian dynamics in high-gradient regions of probability space, this new simulation algorithm circumvents the numerical instabilities of Hamiltonian Monte Carlo when applied to light-tailed probability distributions.  It also achieves machine precision and is the basis of our Python application [super-aLby](https://github.com/michaelfaulkner/super-aLby).

## 🔭  Current research
- Further connections between general symmetry breaking and the correlated dynamics in the LSCO film.
- A review paper on emergent electrostatics, nonergodicity and symmetry breaking in planar XY spin models.

## 🌱  Future plans and interests
- Application of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) to various problems involving atomistic water and long-chain charged polymers.
- Further projects on emergent electrostatics in 2DXY models.
- Analysis of various sampling algorithms using ideas from Bayesian computation.

## 📫  Contact
- Email me at michael.faulkner AT bristol.ac.uk
- As outlined above, you can find more details on [my personal website](https://michaelfaulkner.github.io) and [Bristol webpage](https://research-information.bris.ac.uk/en/persons/michael-faulkner).
- And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my [publications](https://github.com/michaelfaulkner#--academic-publications) and grants.

## 📜  Academic publications
- *Sampling algorithms in statistical physics: a guide for statistics and machine learning*, M. F. Faulkner and S. Livingstone, [arXiv:2208.04751](https://arxiv.org/abs/2208.04751) (2022)
- *JeLLyFysh-Version1.0 — a Python application for all-atom event-chain Monte Carlo*, P. Höllmer, L. Qin, M. F. Faulkner, A. C. Maggs and W. Krauth, [Comput. Phys. Commun. 253, 107168](https://doi.org/10.1016/j.cpc.2020.107168) (2020)
- *Kinetic-energy choice in hybrid/Hamiltonian Monte Carlo*, S. Livingstone, M. F. Faulkner and G. O. Roberts, [Biometrika 106, 303](https://doi.org/10.1093/biomet/asz013) (2019)
- *All-atom computations with irreversible Markov chains*, M. F. Faulkner, L. Qin, A. C. Maggs and W. Krauth, [J. Chem. Phys. 149, 064113](https://doi.org/10.1063/1.5036638) (2018) 
- *An electric-field representation of the harmonic XY model*, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [J. Phys.: Condens. Matter 29, 085402](https://doi.org/10.1088/1361-648X/aa523f) (2017) 
- *From quantum to thermal topological-sector fluctuations of strongly interacting bosons in a ring lattice*, T. Roscilde, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [New J. Phys. 18, 075003](https://doi.org/10.1088/1367-2630/18/7/075003) (2016)
- *Phase order in superfluid helium films*, S. T. Bramwell, M. F. Faulkner, P. C. W. Holdsworth and A. Taroni, [EPL (Europhys. Lett.) 112, 56003](https://doi.org/10.1209/0295-5075/112/56003) (2015)
- *Topological-sector fluctuations and ergodicity breaking at the Berezinskii—Kosterlitz—Thouless transition*, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [Phys. Rev. B 91, 155412](https://doi.org/10.1103/PhysRevB.91.155412) (2015)
