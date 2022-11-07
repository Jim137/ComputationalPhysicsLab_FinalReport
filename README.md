# The TBD Subject of the Final Report

# 1.	Ising Model

## Quick Note:

For a two-states system. there is a model which can be expressed by the following Hamiltonian

$$
\hat H = -J \Sigma _{(i,j)}s_is_j-h\Sigma_j\sigma_j
$$

where $$s_i=\pm 1$$ is the (spin) state of the atom. The first summation is over the nearest-neighbor (i) atom, while the second is summing over external magnetic flux that applied on specific (j) atom.

### Evolving 

If the energy E of a single atom is <0, then it flip. elseif flip with the probability of $$e^{-E\beta}$$ .

## Ref:

[易辛模型 - 維基百科，自由的百科全書 (wikipedia.org)](https://zh.wikipedia.org/wiki/易辛模型)

[ComputationalPhysicsKNA.pdf (ntua.gr)](http://www.physics.ntua.gr/~konstant/ComputationalPhysics/Book/ComputationalPhysicsKNA.pdf) Ch13 p495 / Ch14 p574~581

[Ising model | Blog (rajeshrinet.github.io)](https://rajeshrinet.github.io/blog/2014/ising-model/)

[【71.Ising Model介绍】](https://www.bilibili.com/video/BV1ov411q74F?vd_source=8c2776f7575e52c7f5afbd4b32de74d0)

[Phase transitions | Concepts in Thermal Physics | Oxford Academic (nthu.edu.tw)](https://academic-oup-com.nthulib-oc.nthu.edu.tw/book/26407/chapter/194825582#320632217)



# 2.	Gross–Pitaevskii equation

The time-dependent Gross–Pitaevskii equation:

$$
i\hbar\frac{\partial\Psi(\vec r,t)}{\partial t}= \left[-\frac{\hbar^2}{2m}\nabla^2+V_{ext}(\vec r)+g|\Psi(\vec r,t)|^2\right]\Psi(\vec r,t)
$$

## Quick Note:

Gross–Pitaevskii equation (GPE) can describe the macroscopic state of Bose-Einstein condensates (BCEs).

Several numerical methods, such as the split-step [Crank–Nicolson](https://en.wikipedia.org/wiki/Crank–Nicolson_method) and [Fourier spectral](https://en.wikipedia.org/wiki/Spectral_method) methods, have been used for solving GPE.

## Ref:

[格羅斯–皮塔耶夫斯基方程 - 維基百科，自由的百科全書 (wikipedia.org)](https://zh.wikipedia.org/wiki/格罗斯–皮塔耶夫斯基方程)

[TarkhovAndrei/DGPE (github.com)](https://github.com/TarkhovAndrei/DGPE)

[AshtonSBradley/FourierGPE.jl: Simple Gross-Pitaevskii Equation solver using FFTW (github.com)](https://github.com/AshtonSBradley/FourierGPE.jl)

[GPUE (gpue-group.github.io)](https://gpue-group.github.io/intro/)



# 3.	Lattice Boltzmann methods

## Quick Note:

### Something can do

Simulate a two-dimensional non-viscous fluid with the same equation of state as that of an adiabatic ideal gas. Based on the simulation results, discuss the differences found between a seven-velocity triangular lattice model and a nine-velocity square lattice model.

### Evolving

Collision step

$$
f_i(\vec x,t+\delta_t) = f_i(\vec x,t) + \frac{f_i^{eq}(\vec x,t)-f_i(\vec x,t)}{\tau_f}
$$

Streaming step

$$
f_i(\vec x+\vec e_i,t+\delta_t) = f_i(\vec x,t)
$$

### Applications

- Porous Media flows
- Biomedical Flows
- Earth sciences (Soil filtration)
- Energy Sciences (Fuel Cells)

## Ref:

[Lattice Boltzmann methods - Wikipedia](https://en.wikipedia.org/wiki/Lattice_Boltzmann_methods#Mathematical_equations_for_simulations)

[A concise python implementation of the lattice Boltzmann method on HPC for geo-fluid flow](https://par.nsf.gov/servlets/purl/10253868)

[An Introduction to Computational Physics, Second Edition.pdf (lagout.org)](https://doc.lagout.org/Others/An%20Introduction%20to%20Computational%20Physics%2C%20Second%20Edition.pdf) Ch9.8 p279~282

[Create Your Own Lattice Boltzmann Simulation (With Python) | by Philip Mocz | The Startup | Medium](https://medium.com/swlh/create-your-own-lattice-boltzmann-simulation-with-python-8759e8b53b1c)

[News — pylbm v0.8.0 Manual](https://pylbm.readthedocs.io/en/latest/)

[jviquerat/lbm: A simple full-python 2D lattice-Boltzmann code (github.com)](https://github.com/jviquerat/lbm)



# 4.	Go

## Quick Note:

White/Black stones can be viewed as two energy states. and we can use Ising model and Hamiltonian to precise characterize the intense interaction in Go gaming.

### Something we can do

- Make a Go AI with genetic algorithm
- Go matches analyzing by Ising model

## Ref:

[Go game formal revealing by Ising mode(arxiv.org)](https://arxiv.org/ftp/arxiv/papers/1710/1710.07360.pdf)

[Agah_GeneticAlgorithms.pdf (ku.edu)](https://kuscholarworks.ku.edu/bitstream/handle/1808/19816/Agah_GeneticAlgorithms.pdf?sequence=1)

[lxucs/go-game-easy: A simplified version of Go game in Python, with AI agents built-in and GUI to play. (github.com)](https://github.com/lxucs/go-game-easy)

[How to build your own AlphaZero AI using Python and Keras | by David Foster | Applied Data Science | Medium](https://medium.com/applied-data-science/how-to-build-your-own-alphazero-ai-using-python-and-keras-7f664945c188)

[Implementing the Game of Go (Part 1) (moderndescartes.com)](https://www.moderndescartes.com/essays/implementing_go/)

[Establishing a discrete Ising model for zeolite deactivation: inspiration from the game of Go - Catalysis Science & Technology (RSC Publishing)](https://pubs.rsc.org/en/Content/ArticleLanding/2017/CY/C7CY00331E)

[An Introduction to Computational Physics, Second Edition.pdf (lagout.org)](https://doc.lagout.org/Others/An%20Introduction%20to%20Computational%20Physics%2C%20Second%20Edition.pdf) Ch11 p.323~345



# Others

[Machine Learning Methods on 2D Ising Mode (warwick.ac.uk)](https://warwick.ac.uk/fac/sci/physics/staff/academic/roemer/publications/Thesis_Civitcioglu_2020.pdf)

[cluster.pdf (helsinki.fi)](https://www.mv.helsinki.fi/home/rummukai/simu/cluster.pdf)

