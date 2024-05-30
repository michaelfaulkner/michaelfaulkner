## 👋 About me

I'm an [Assistant Professor](https://warwick.ac.uk/fac/sci/eng/people/michael_faulkner/) in the [Warwick Centre for Predictive Modelling](https://warwick.ac.uk/fac/sci/wcpm/).  Primarily I'm a computational statistical physicist, specialising in:
- Emergent electrostatics, slow mixing and correlated dynamics in systems that experience the Berezinskii-Kosterlitz-Thouless phase transition, eg, certain planar magnets, superfluids and superconductors.
- Molecular simulation in soft-matter physics, with a focus on electrostatics, high precision and numerical stability.
- Monte Carlo sampling algorithms in statistical physics and Bayesian computational statistics, with a particular interest in piecewise deterministic Markov processes (PDMPs) such as event-chain Monte Carlo.

I started my academic career as a PhD student at [University College London](https://www.ucl.ac.uk/condensed-matter-material-physics/) and [Ecole normale supérieure de Lyon](http://www.ens-lyon.fr/PHYSIQUE/teams/physique-theorique/research-topics/statistical-physics), under the co-supervision of [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique).  After a short postdoc and teaching position at [Bristol Mathematics](https://www.bristol.ac.uk/maths/), I then moved to [Bristol Physics](https://www.bristol.ac.uk/physics/research/theory/) in August 2017 after winning an EPSRC postdoctoral research fellowship.  I was also a visiting scientist at [Ecole normale supérieure](http://www.phys.ens.fr/?lang=fr) from September 2017 to October 2018, and won a Max Planck Institute research fellowship to visit the [Max Planck Institute for the Physics of Complex Systems](https://www.pks.mpg.de) in Dresden in April 2018.

My [publications](https://github.com/michaelfaulkner#--academic-publications) are listed below. For more details in general, please visit 
- [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra)
- [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F)
- [ORCiD](https://orcid.org/0000-0002-9116-2878)
- [My Warwick webpage](https://warwick.ac.uk/fac/sci/eng/people/michael_faulkner/)
- [My personal website](https://michaelfaulkner.github.io)

## 👨‍🔧  Main contributions to Github 
- An original co-author of [super-aLby](https://github.com/michaelfaulkner/super-aLby) — a mediator-based Python application for super-relativistic, Hamiltonian, Metropolis and Wolff Monte Carlo in statistical physics and Bayesian computation.
- An original co-author of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) — a mediator-based Python-C application for atomistic event chain Monte Carlo simulation in soft matter.
- The sole author of [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) — a Fortran-Python application for Metropolis and event chain Monte Carlo simulation of 2DXY models and the 2D lattice-field electrolyte.

## 🔑 Key scientific achievements
### Planar materials
- Discovered [general symmetry breaking at the Berezinskii-Kosterlitz-Thouless (BKT) transition](https://doi.org/10.1103/PhysRevB.109.085405).  This resolved the paradox of symmetry breaking being observed in many BKT experiments in spite of a predicted absence of spontaneous symmetry breaking.  Examples include [superconducting films of lanthanum strontium copper oxide (LSCO)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503).  The result provides a model for symmetry-restoring (or memory) timescales in a wide array of experimental systems.
- Defined the above new concept — [general symmetry breaking](https://doi.org/10.1103/PhysRevB.109.085405) — which encompasses both spontaneous symmetry breaking and the experimental anomalies.
- Discovered [topological ergodicity breaking at the BKT transition](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412) in the 2D lattice-field Coulomb liquid (with [Steve Bramwell](https://www.ucl.ac.uk/physics-astronomy/people/professor-steven-bramwell) and [Peter Holdsworth](http://www.ens-lyon.fr/en/research/honors-and-awards/peter-holdsworth-physicist-laboratoire-de-physique)).  This was cited as a possible explanation for [correlated resistance fluctuations](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.94.134503) at the superconducting transition in the LSCO film and proved to induce the above general symmetry breaking.
- Developed the grand-canonical analogue of the [Maggs lattice-field model of Coulomb liquids](https://doi.org/10.1103/PhysRevLett.88.196402) and showed its equivalence to [the Villain model](https://doi.org/10.1051/jphys:01975003606058100) of planar magnets (see Section II and Appendix B of [the paper on topological ergodicity breaking](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.91.155412)).  We then...
- ...presented an [electric-field representation of the harmonic XY model](https://doi.org/10.1088/1361-648X/aa523f) — a more realistic model of planar magnets, superfluids and superconductors — which mapped the topological ergodicity breaking to the ergodic exclusion of global phase twists in the magnetic spins / condensate wavefunction.

### Molecular simulation and event-chain Monte Carlo
- Designed [an event-chain algorithm](https://doi.org/10.1063/1.5036638) for numerically stable and determinstic all-atom molecular Coulomb simulations in soft matter (with [Liang Qin](https://scholar.google.com/citations?user=rGW6nKUAAAAJ), [Tony Maggs](https://turner.pct.espci.fr/~amaggs/index2.html) and [Werner Krauth](http://www.lps.ens.fr/~krauth/index.php/Main_Page)).  This is the only molecular simulation algorithm that mixes (equilibrates from a random initial configuration) Coulomb-based models in *O(N log(N))* computations, where *N* is the number of particles.  It also achieves machine precision and is the basis of...
- ...our mediator-based Python-C application [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh), which we set out in detail [here](https://doi.org/10.1016/j.cpc.2020.107168) (also with [Philipp Höllmer](https://scholar.google.com/citations?user=TzZkSGMAAAAJ&hl=fr&oi=sra)).

### Sampling algorithms and interface with Bayesian computational statistics
- Co-produced an [in-depth article](https://arxiv.org/abs/2208.04751) for stats/machine learning on statistical physics and its sampling algorithms.  We took a particular interest in phase transitions and event-chain Monte Carlo, presenting the latter in the language of PDMPs in Bayesian computations.  This project used [super-aLby](https://github.com/michaelfaulkner/super-aLby) and [xy-type-models](https://github.com/michaelfaulkner/xy-type-models) to simulate the models presented.  We are now building on the connections presented in the paper.
- Designed [super-relativistic Monte Carlo](https://doi.org/10.1093/biomet/asz013) for high-stability simulation of probability models in Bayesian computation (with statisticians [Sam Livingstone](https://www.ucl.ac.uk/statistics/department-information/staff/dr-samuel-livingstone) and [Gareth Roberts](https://warwick.ac.uk/fac/sci/statistics/staff/academic-research/roberts/) — see section 5.2 of [the linked paper](https://doi.org/10.1093/biomet/asz013) for details).  By slowing down the Newtonian dynamics in high-gradient regions of probability space, this new simulation algorithm circumvents the numerical instabilities of Hamiltonian Monte Carlo when applied to light-tailed probability distributions.  It also achieves machine precision and is the basis of our Python application [super-aLby](https://github.com/michaelfaulkner/super-aLby).

## 🔭  Current research
- Developing PDMPs to resolve correlated dynamics in the LSCO film.
- A review paper on emergent electrostatics, topological nonergodicity and symmetry breaking in planar XY spin models.
- A PDMP sampler for agent-based epidemic models.

## 🌱  Future plans and interests
- PDMPs for correlated dynamics at continuous phase transitions in statistical physics and Bayesian computation.
- PDMP sampling for computational quantum field theory.
- Application of [JeLLyFysh](https://github.com/jellyfysh/JeLLyFysh) to various problems involving atomistic water and long-chain charged polymers.
- Further projects on emergent electrostatics in 2DXY models.

## 🚀 Vacancies
- I have [an open PhD position](https://warwick.ac.uk/fac/sci/hetsys/themes/projectopportunities/hp2024-10/) in my group.  The project will develop advanced simulation algorithms to characterise strongly correlated system dynamics in both condensed matter and agent-based epidemic modelling.  Informal enquiries to michael.faulkner [AT] warwick.ac.uk are welcome.

## 📫  Contact
- Email me at michael DOT faulkner AT warwick DOT ac DOT uk
- As outlined above, you can find more details on [my personal website](https://michaelfaulkner.github.io) and [Warwick webpage](https://warwick.ac.uk/fac/sci/eng/people/michael_faulkner/).
- And [Google Scholar](https://scholar.google.com/citations?user=wDxigWUAAAAJ&hl=fr&oi=sra), [arXiv](https://arxiv.org/search/?searchtype=author&query=Faulkner%2C+M+F) and [ORCiD](https://orcid.org/0000-0002-9116-2878) detail my [publications](https://github.com/michaelfaulkner#--academic-publications) and grants.

## 📜  Academic publications
- *Sampling algorithms in statistical physics: a guide for statistics and machine learning*, M. F. Faulkner and S. Livingstone, [Statist. Sci. 39, 137](https://doi.org/10.1214/23-STS893) (2024) [[arXiv:2208.04751](https://arxiv.org/abs/2208.04751)]
- *Symmetry breaking at a topological phase transition*, M. F. Faulkner, [Phys. Rev. B 109, 085405](https://doi.org/10.1103/PhysRevB.109.085405) (2024) [[arXiv:2209.03699](https://arxiv.org/abs/2209.03699)]
- *JeLLyFysh-Version1.0 — a Python application for all-atom event-chain Monte Carlo*, P. Höllmer, L. Qin, M. F. Faulkner, A. C. Maggs and W. Krauth, [Comput. Phys. Commun. 253, 107168](https://doi.org/10.1016/j.cpc.2020.107168) (2020) [[arXiv:1907.12502](https://arxiv.org/abs/1907.12502)]
- *Kinetic-energy choice in hybrid/Hamiltonian Monte Carlo*, S. Livingstone, M. F. Faulkner and G. O. Roberts, [Biometrika 106, 303](https://doi.org/10.1093/biomet/asz013) (2019) [[arXiv:1706.02649](https://arxiv.org/abs/1706.02649)]
- *All-atom computations with irreversible Markov chains*, M. F. Faulkner, L. Qin, A. C. Maggs and W. Krauth, [J. Chem. Phys. 149, 064113](https://doi.org/10.1063/1.5036638) (2018) [[arXiv:1804.05795](https://arxiv.org/abs/1804.05795)]
- *An electric-field representation of the harmonic XY model*, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [J. Phys.: Condens. Matter 29, 085402](https://doi.org/10.1088/1361-648X/aa523f) (2017) [[arXiv:1610.06692](https://arxiv.org/abs/1610.06692)]
- *From quantum to thermal topological-sector fluctuations of strongly interacting bosons in a ring lattice*, T. Roscilde, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [New J. Phys. 18, 075003](https://doi.org/10.1088/1367-2630/18/7/075003) (2016) [[arXiv:1602.06247](https://arxiv.org/abs/1602.06247)]
- *Phase order in superfluid helium films*, S. T. Bramwell, M. F. Faulkner, P. C. W. Holdsworth and A. Taroni, [EPL (Europhys. Lett.) 112, 56003](https://doi.org/10.1209/0295-5075/112/56003) (2015) [[arXiv:1508.07773](https://arxiv.org/abs/1508.07773)]
- *Topological-sector fluctuations and ergodicity breaking at the Berezinskii—Kosterlitz—Thouless transition*, M. F. Faulkner, S. T. Bramwell and P. C. W. Holdsworth, [Phys. Rev. B 91, 155412](https://doi.org/10.1103/PhysRevB.91.155412) (2015) [[arXiv:1502.00815](https://arxiv.org/abs/1502.00815)]
