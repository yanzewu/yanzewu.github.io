
[< home](index.htm)


# Research

## Ultrafast Electron Relaxation in Metal Nanostructures

Metal nanostructures are known to be ideal photocatalysts as they are excellent absorbers of visible lights and also great electron transmitters. Microscopically, the metal can transfrom the light energy to hot electrons within 10 femtoseconds. After that, the newly generated hot electrons can choose to catalyze the molecule or just relax upon colliding with remaining cool electrons. The later process, however, is less included in theoretical modeling. With efficient tight-binding approaches and GPU acceleration, we are able to see the electron relaxation in real time.

<div align='center'>
<video width="50%" controls>
<source src="imgs/rt-charges.mp4" type="video/mp4">
</video>
<br>Real-time evolution of hot electron and hole distributions in silver nanoparticle.
</div>
<br>
- __Wu, Y.__, & Schatz, G. C. (2026). Real-Time Electron-Electron Scattering Dynamics in Plasmonic Nanostructures. _arXiv preprint_ arXiv:2603.05695

## Phonon Induced Electronic Spin Polarization

In molecular systems, nuclear dynamics is rarely considered as an option to manipuate electronic spin. However, in our quantum simualtions, we found phonon-induced spin polarization is not uncommon in certain systems, namely systems with a 'complex-valued' Hamiltonian. With an unequilibrated initial condition, a spin polarization of nearly 100% can be achieved in certain reaction channels. An theoretical understanding of these effects may explain the mechanism of magnetic chemical reactions and help discover useful molecular spintronics.

<div align='center'>
<img src="imgs/pe.png" width="50%" align="middle">
<br>Schematic representation of spin polarization in our model system.
</div>
<br>
- __Wu, Y.__, & Subotnik, J. E. (2021). Electronic spin separation induced by nuclear motion near conical intersections. _Nature Communications_, 12(1), 700.
- __Wu, Y.__, Miao, G., & Subotnik, J. E. (2020). Chemical Reaction Rates for Systems with Spin-Orbit Coupling and an Odd Number of Electrons: Does Berry’s Phase Lead to Meaningful Spin-Dependent Nuclear Dynamics for a Two State Crossing?. _The Journal of Physical Chemistry A_, 124(37), 7355-7372

## Modeling of Spin Chemical Dynamics

Unlike energy, momentum and angular momentum are rarely paid attention in chemical dynamics. However the recent discovery of chirality-induced spin selectivity (CISS) effects have challenged this idea, where the spin angular momentum can affect electric conductivity and reaction rates. A correct modeling of these phenomena must take care of hyperfine degeneracy (doublets, triplets, etc.) where traditional approaches often neglect. Based on a phase-space approach, we have developed a new modeling technique that accurately captures all the angular momentum transfer between hyberfine levels, and enables us to see the effect of spin on chemical reaction dynamics.

<div align='center'>
<img src="imgs/pssh.png" width="50%" align="middle">
<br>Benchmark between our method (PSSH) and traditional method (FSSH) in modeling a two-level dynamic system.
</div>
<br>
- __Wu, Y.__, Bian, X., Rawlinson, J. I., Littlejohn, R. G., & Subotnik, J. E. (2022). A phase-space semiclassical approach for modeling nonadiabatic nuclear dynamics with electronic spin. _The Journal of Chemical Physics_, 157(1), 011101.
- __Wu, Y.__, Rawlinson, J., Littlejohn, R. G., & Subotnik, J. E. (2024). Linear and angular momentum conservation in surface hopping methods. _The Journal of Chemical Physics_, 160(2).
- __Wu, Y.__, & Subotnik, J. E. (2023). A quantum-classical Liouville formalism in a preconditioned basis and its connection with phase-space surface hopping. _The Journal of Chemical Physics_, 158(2)