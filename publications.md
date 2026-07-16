---
layout: default
title: Publications
---

SUBMITTED PAPERS
---

S.P., G. Gabard, T. Chaumont-Frelet, A. Modave (2026)<br>
**A HDG method with transmission variables for time-harmonic wave propagation problems with constant coefficients**<br>
*Submitted for publication*
<div class="paper-links">

  <a href="https://hal.science/hal-05654780" target="_blank" rel="noopener noreferrer">
    Preprint
  </a>

</div>

---

PEER-REVIEWED JOURNAL PAPERS
---

S.P., G. Gabard, T. Chaumont-Frelet, A. Modave (2025)<br>
**A hybridizable discontinuous Galerkin method with transmission variables for time-harmonic acoustic problems in heterogeneous media**<br>
*Journal of Computational Physics*
<div class="paper-links">

  <a href="https://doi.org/10.1016/j.jcp.2025.114009" target="_blank" rel="noopener noreferrer">
    Link
  </a>

  <a href="https://inria.hal.science/hal-04821539/" target="_blank" rel="noopener noreferrer">
    Preprint
  </a>

</div>
---

THESIS
---

S.P. (2025)<br>
**Discontinuous Galerkin finite element methods with transmission variables for time-harmonic wave propagation**<br>

<div class="abstract-container">

  <button class="abstract-button" onclick="toggleAbstract(this)">
    Abstract
  </button>

  <div class="abstract-text">
    The goal of this thesis is to develop wave-specific discontinuous Galerkin (DG) methods for wave-propagation phenomena. Linear systems arising from finite element discretization techniques are often difficult to solve due to ill-conditioning issues related to intrinsic properties of time-harmonic problems. DG methods are very versatile and offer a wide framework for formulations that allow the use of fast iterative algorithms as well as non-standard basis functions. In addition, part of this thesis is motivated by the intuition that embedding the oscillating nature of the physical problem into the discretization method should lead to an improvement of the properties of the associated linear system. We consider a variant of the hybridizable discontinuous Galerkin (HDG) method with upwind numerical fluxes. Unlike the standard approach, the hybridization process is achieved using transmission variables whose definitions are driven by the physics of the problem. The resulting method, called the CHDG method, delivers an overall improvement of the speed of convergence of iterative procedures when compared to standard DG and HDG methods. We extend the theory of CHDG, which was initially studied for acoustic problems, to general time-harmonic problems with numerical tests focusing on aeroacoustics in homogeneous media. Moreover, inspired by recent studies on domain decomposition methods, we target another extension of CHDG that includes high-order transmission variables with a focus for the theory and the numerical tests on acoustic for both homogeneous and heterogeneous media. Lastly, with the idea of combining wave-tailored interface treatments with a wave-based basis method, we investigate a Trefftz DG method with propagative plane-wave basis functions applied to Helmholtz problems complemented by high-order absorbing boundary conditions. The numerical methods are studied by using two-dimensional numerical benchmarks implemented in dedicated MATLAB codes.
  </div>

</div>

<div class="paper-links">

  <a href="https://theses.fr/s347043" target="_blank" rel="noopener noreferrer">
    Link
  </a>

  <a href="{{ '/assets/pdf/Pescuma_PhD_thesis.pdf' | relative_url }}"
     target="_blank"
     rel="noopener noreferrer">
    PDF
  </a>

</div>
---

S.P. (2023)<br>
**A Trefftz discontinuous Galerkin method with absorbing boundary conditions for the numerical simulation of the Helmholtz problem**<br>

<div class="abstract-container">

  <button class="abstract-button" onclick="toggleAbstract(this)">
    Abstract
  </button>

  <div class="abstract-text">
    The numerical simulation of Helmholtz problems in the time-harmonic acoustic framework set in unbounded domains requires a mesh based approach in bounded numerical domains. Therefore, we present a Trefftz method, which is a particular Discontinuous Galerkin method, applied to the problem complemented by Absorbing Boundary Conditions. Trefftz methods have been largely studied in the framework of Helmholtz equation and have turned out to be suitable. In particular, the use of propagative plane-waves is effective in approximating the solution. Nevertheless, their use is still limited by conditioning issues that arise whenever the approximate space becomes too large. The combination of the wave-based Trefftz method and the relative Ultra Weak Variational Formulation with Absorbing Boundary Conditions represents a novelty that we aim at studying and investigating in the present work. It leads to a new formulation of the problem whose numerical results are exploited to evaluate the efficiency of the approach.
  </div>

</div>


<div class="paper-links">

  <a href="https://www.politesi.polimi.it/handle/10589/203292" target="_blank" rel="noopener noreferrer">
    Link
  </a>

  <a href="{{ '/assets/pdf/Pescuma_Polimi_thesis.pdf' | relative_url }}"
     target="_blank"
     rel="noopener noreferrer">
    PDF
  </a>

</div>
