# **Research**

---

</br>

## Preparing quantum states with measurements

<figure>
  <img src="/MPS.png" alt="image" width="500" height="auto">
  <figcaption>Algorithm to prepare a matrix-product state. Figure from <a href="https://doi.org/10.1103/PhysRevLett.132.040404">PRL (2024)</a>.</figcaption>
</figure>

</br>

Measurements are often solely thought of as means to extract information from a quantum state. However, measurement can also be used as an *active ingredient* in quantum protocols. This line of work explores how the resources (such as circuit depth) needed to transform a given state to a target one can be *drastically reduced* by utilizing measurements.

The problem of state preparation is evidently motivated by the *practical need* to prepare states in quantum devices, e.g., for quantum computing and simulation. However, it also has a more *fundamental flavor* to it since it naturally connects to the classification of topological phases.


</br>

### Selected Publications:


</br>

*   *Characterizing MPS and PEPS Preparable via Measurement and Feedback,*  
    Zhang, Gopalakrishnan, **Styliaris**
    [\[PRX Quantum (2024)\]](https://doi.org/10.1103/PRXQuantum.5.040304)


</br>

*   *Approximating many-body quantum states with quantum circuits and measurements,*  
    Piroli, **Styliaris**, Cirac
    [\[PRL (2024)\]](https://journals.aps.org/prl/accepted/8f07aY05E9e18f84042543493780b9c85f774fc18)


</br>

*   *Preparation of Matrix Product States with Log-Depth Quantum Circuits,*  
    Malz\*, **Styliaris\***, Wei\*, Cirac [\[PRL (2024)\]](https://doi.org/10.1103/PhysRevLett.132.040404)
    [\[Talk at TQC 2024\]](https://www.youtube.com/watch?v=kIUDV3AvuiM&t=3600s)
  
</br>

*   *Quantum Circuits Assisted by Local Operation and Classical Communication: Transformations and Phases of Matter,*  
    Piroli, **Styliaris**, Cirac [\[PRL (2021)\]](https://doi.org/10.1103/PhysRevLett.127.220503)
     [\[Talk at QIP 2022\]](https://youtu.be/mct_FB3O-Ms?si=vyQbgSB3A_uF7tLR)
     
</br>

### Review Article:

</br>

*   *From Bits to Qubits: The Theory and Practice of Quantum Data Encoding,*  
    Zhang\*, Rattew\*, Wu, **Styliaris**, Sun, Koczor, Yuan [\[arXiv (2026)\]](https://doi.org/10.48550/arXiv.2609.08058)


----

</br>

## Theory of tensor networks

<figure>
  <img src="/TN.png" alt="image" width="500" height="auto">
  <figcaption>Multiple copies of a random tensor network. Figure from <a href="https://doi.org/10.1103/PRXQuantum.4.030330">PRX Quantum (2023)</a>.</figcaption>
</figure>


</br>

The many-body Hilbert space is large, as it grows *exponentially* with the number of constituents \[*"no one can hear you scream there"*, as I learned from [Todd Brun](https://viterbi.usc.edu/directory/faculty/Brun/Todd)\]. However, when interactions are local, the corresponding low-energy physics is *captured by tensor-networks*. This not only allows for an *efficient* description of the relevant quantum states and operations, but also provides a general framework for many-body physics, in the *language of quantum information*.

</br>


### Selected Publications:

</br>

*   *Structure and Classification of Matrix Product Quantum Channels,*  
    Stucchi, Cirac, Trivedi, **Styliaris** [\[PRL (2026)\]](https://journals.aps.org/prl/accepted/10.1103/4216-bgrp)

</br>

*   *Quantum Circuits for Matrix-Product Unitaries,*  
    **Styliaris\***, Trivedi\*, Cirac [\[PRL (2025)\]](https://doi.org/10.1103/yshb-hmml)  [\[Talk at QIP 2026\]](https://qip2026.lu.lv/)

</br>

*   *Matrix-product unitaries: Beyond quantum cellular automata,*  
    **Styliaris**, Trivedi, Pérez-García, Cirac [\[Quantum (2025)\]](https://doi.org/10.22331/q-2025-02-25-1645)
    
</br>

*   *Typical Correlation Length of Sequentially Generated Tensor Network States,*  
    Haag, Baccari, **Styliaris** [\[PRX Quantum (2023)\]](https://doi.org/10.1103/PRXQuantum.4.030330)

</br>

----

</br>

## Exactly solvable quantum states and dynamics

<figure>
  <img src="/Space_time.png" alt="image" width="700" height="auto">
  <figcaption>A quantum circuit of spacetime quantum channels. Figure from <a href="https://doi.org/10.22331/q-2023-05-24-1020">Quantum (2023)</a>.</figcaption>
</figure>

</br>

Dual-unitary circuits have emerged as a rich model of quantum dynamics. While this class includes both *integrable and chaotic* models, it allows for the analytical solution of *correlation functions*. The defining property of these circuits is that, when the role of *space and time is exchanged*, the corresponding evolution remains physical, i.e., unitary.

No realistic quantum system is perfectly isolated. Fortunately, it turns out that the ideas of dual-unitarity can be extended to the realm of open systems. This is achieved by postulating the analogous symmetry between space and time (what we dubbed *spacetime quantum channels*), giving rise to a rich class of *exactly solvable open-system dynamics*.

We have explored implications of this framework for tensor networks and quantum computation. Spacetime channels give rise to a large class of 2D tensor-network states with exactly solvable single and two-body correlation functions. In general, this problem is known to be intractable. In quantum computing, spacetime channels can be turned into practically relevant *benchmarking schemes* by *averaging* variants of the (otherwise arbitrary) target computation. The resulting average quantum computation can be probed classically, while its individual instances could remain hard.

</br>

### Selected Publications:


</br>

*   *Average-computation benchmarking for local expectation values in digital quantum devices,*  
     Baccari\*, Kos\*, **Styliaris\*** [\[PR Research (Letter) (2026)\]](https://doi.org/10.48550/arXiv.2507.18708)

</br>

*   *Adiabatic quantum state preparation in integrable models,*  
    Lutz, Piroli, **Styliaris**, Cirac [\[Quantum (2026)\]](https://doi.org/10.22331/q-2026-03-18-2032)

</br>

*   *Dual-isometric Projected Entangled Pair States,*  
    Yu, Cirac, Kos\*, **Styliaris\*** [\[PRL (2024)\]](https://journals.aps.org/prl/accepted/33071Y7cFd81329590089116f7a025c305b9efdc0)
    
</br>

*   *Circuits of space and time quantum channels,*  
    Kos\*, **Styliaris\*** [\[Quantum (2023)\]](https://doi.org/10.22331/q-2023-05-24-1020)  [\[Perspective on our article by Shane Dooley\]](https://doi.org/10.22331/qv-2023-07-26-75)


</br>

----



</br>


## Quantum information theory & Quantum computing

<figure>
  <img src="/monotones_BW.png" alt="image" width="600" height="auto">
  <figcaption>Symmetries in Markovian dynamics give rise to monotones. Figure from <a href="https://doi.org/10.22331/q-2020-04-30-261">Quantum (2020)</a>.</figcaption>
</figure>

</br>

Quantum information offers a *powerful language* for understanding quantum phenomena through the lens of *information processing* and *computation*. I enjoy thinking about different problems from the perspective of quantum information, ranging from measurement incompatibility, to information scrambling and symmetries in open systems.


</br>

### Selected Publications:


</br>

*   *Accuracy guarantees and quantum advantage in analogue open quantum simulation with and without noise,*  
    Kashyap, **Styliaris**, Mouradian, Cirac, Trivedi [\[PRX (2025)\]](https://journals.aps.org/prx/accepted/64071Ke6Ebe1f30bc85b6de6a6d889a50f914592c)

</br>

*   *Computable Rényi mutual information: Area laws and correlations,*  
    Scalet, Alhambra, **Styliaris**, Cirac [\[Quantum (2021)\]](https://doi.org/10.22331/q-2021-09-14-541)

</br>

*   *Information Scrambling over Bipartitions: Equilibration, Entropy Production, and Typicality,*  
    **Styliaris**, Anand, Zanardi [\[PRL (2021)\]](https://doi.org/10.1103/PhysRevLett.126.030601)

</br>

*   *Symmetries and monotones in Markovian quantum dynamics,*  
    **Styliaris**, Zanardi [\[Quantum (2020)\]](https://doi.org/10.22331/q-2020-04-30-261)
    
</br>

*   *Fundamental Limitations to Local Energy Extraction in Quantum Systems,*  
    Alhambra, **Styliaris**, Rodríguez-Briones, Sikora, Martín-Martínez [\[PRL (2019)\]](https://doi.org/10.1103/PhysRevLett.123.190601)    

</br>

*   *Quantifying the Incompatibility of Quantum Measurements Relative to a Basis,*  
    **Styliaris**, Zanardi [\[PRL (2019)\]](https://doi.org/10.1103/PhysRevLett.123.070401)



</br>

----
