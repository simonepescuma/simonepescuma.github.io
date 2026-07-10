## New submitted paper

<div class="featured-paper">

  <div class="paper-text">

    <p><strong>S. Pescuma, G. Gabard, T. Chaumont-Frelet, A. Modave (2026)</strong></p>

    <h3>
      A HDG method with transmission variables for time-harmonic wave propagation problems with constant coefficients
    </h3>
    
<p class="abstract">
  Iterative finite element solvers for time-harmonic wave problems are notoriously slow to converge, owing to fundamental properties of these problems. We present a variant of the hybridizable discontinuous Galerkin (HDG) method that is better suited to fast iterative solution. Unlike the standard hybridization strategy, which eliminates physical unknowns by introducing an auxiliary numerical flux on element faces, our approach instead introduces a transmission variable on those faces. For Helmholtz problems, this reformulation, known as CHDG, has been shown to significantly accelerate the convergence of iterative schemes relative to standard HDG. The present work extends CHDG to a general framework covering wave propagation problems with constant coefficients, capable of handling diverse wave types in a unified manner. We prove that the resulting hybridized system is well-posed and amenable to fixed-point iteration. As a practical application, we apply the method to the time-harmonic linearized Euler equations with a uniform subsonic mean flow. The method is illustrated through two-dimensional numerical benchmarks involving both sound and vorticity waves, with a systematic comparison of the convergence behaviour of several iterative schemes across a range of configurations.
</p>

    <div class="paper-links">

      <a href="https://hal.science/hal-05654780" target="_blank" rel="noopener noreferrer">
        Preprint (HAL)
      </a>

    </div>

  </div>

  <div class="paper-image">

    <img src="{{ '/assets/images/paper2026.png' | relative_url }}" alt="Paper figure">

  </div>

</div>
