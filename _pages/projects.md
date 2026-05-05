---
title: "Projects"
layout: gridlay
sitemap: false
permalink: /projects/
---

<style>
.project-category {
  margin: 45px 0 20px 0;
}

.project-card {
  background: #f8f9fa;
  border-radius: 12px;
  padding: 26px;
  margin: 26px 0;
}

.project-card h4 {
  margin-top: 0;
}

.project-meta {
  color: #555;
  margin-bottom: 12px;
}

.project-card ul {
  margin-top: 12px;
}

.project-card li {
  margin-bottom: 6px;
}

.project-media {
  text-align: center;
  margin-top: 22px;
}

.project-media img,
.project-media video,
.project-media iframe {
  display: block;
  margin: 20px auto;
  width: 100%;
  max-width: 850px;
  height: auto;
  aspect-ratio: 16 / 9;
  object-fit: contain;
  border: 0;
  border-radius: 8px;
}

.project-media-wide img,
.project-media-wide video,
.project-media-wide iframe {
  display: block;
  margin: 24px auto;
  width: 100%;
  max-width: 1100px;
  height: auto;
  aspect-ratio: 16 / 9;
  object-fit: contain;
  border: 0;
  border-radius: 8px;
}

.project-links {
  text-align: center;
  margin-top: 10px;
}
</style>

<h2>Academic Research</h2>

<p>
My research develops physics-based, computational, and data-driven models to understand fluid flow,
transport, and environmental change across Earth and planetary systems.
</p>

<hr>

<div class="project-category">
<h3>Cryosphere Hydrology</h3>

<div class="project-card">
<h4>Firn Densification and Meltwater Percolation</h4>

<p class="project-meta">
<b>Collaborators:</b>
Surendra Adhikari (NASA JPL), C. Max Stevens (NASA Goddard), Asa Rennermalm (Rutgers),
Jing Xiao (Rutgers), Cyril Grima (UT Austin), Anja Rutishauser (GEUS), Marc Hesse (UT Austin), Reed Maxwell (Princeton)
</p>

<p>
Developing multidimensional models for meltwater infiltration, refreezing, and ice-layer formation in polar firn.
</p>

<ul>
<li>Developed a multidimensional three-phase snow-water-air flow model for polar firn</li>
<li>Validated model predictions against field observations and analytical benchmarks</li>
<li>Simulated ice-layer formation under repeated melt events at the DYE-2 site in Greenland</li>
</ul>

<div class="project-media">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/S2_firn_video_4000m_with_classification_pcolormesh.mp4' | relative_url }}" type="video/mp4">
</video>

<p class="project-links">
<a href="https://arxiv.org/pdf/2604.11488" target="_blank">Preprint (2025)</a>,
<a href="https://doi.org/10.1017/jog.2025.10055" target="_blank">Paper (2025)</a>,
<a href="https://doi.org/10.1029/2024GL109893" target="_blank">Preprint (2024)</a>...
</p>

</div>
</div>


<div class="project-card">
<h4>Firn Aquifers</h4>

<p class="project-meta">
<b>Collaborators:</b>
Howard Stone and Reed Maxwell (Princeton University)
</p>

<p>
Developing reduced-order models for the expansion of aquifers in cold firn.
</p>

<ul>
<li>Formulated a vertically integrated model for aquifer growth in cold firn</li>
<li>Reduced computational cost by approximately 20 times relative to fully resolved simulations</li>
<li>Quantified the impact of firn temperature on aquifer expansion dynamics</li>
</ul>

<div class="project-media">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/VideoS2_ColdFirnAquifer3D.mp4' | relative_url }}" type="video/mp4">
</video>
</div>
</div>
</div>

<hr>

<div class="project-category">
<h3>Terrestrial Hydrology</h3>

<div class="project-card">
<h4>Integrated Hydrologic Modeling with ParFlow and Community Land Model</h4>

<p class="project-meta">
<b>Collaborators:</b>
Nicholas Jadallah and Reed Maxwell (Princeton University)
</p>

<p>
Investigating how physical process representations affect large-scale integrated hydrologic simulations.
</p>

<ul>
<li>Quantified the role of capillary forcing across spatial scales in coupled hydrologic models</li>
<li>Reformulated snow hydrology from a bucket-based representation toward a Darcy-based framework</li>
<li>Evaluated model behavior against remote sensing products and field observations</li>
</ul>

<div class="project-media-wide">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/lilwashita_SWE_mobile.mp4' | relative_url }}" type="video/mp4">
</video>
</div>
</div>

<div class="project-card">
<h4>Physics-Informed Neural Networks for Groundwater Flow</h4>

<p class="project-meta">
<b>Collaborators:</b>
Dingcheng Luo, Yiran Shen, Eric Hiatt, and Marc Hesse (UT Austin)
</p>

<p>
Developed data-driven frameworks to infer governing equations and parameters in groundwater systems.
</p>

<ul>
<li>Inferred groundwater flow equations directly from sparse observational data</li>
<li>Estimated hydraulic conductivity and boundary conditions in transient seepage problems</li>
<li>Assessed PINN robustness under model-data mismatch and scaling limitations</li>
</ul>

<div class="project-media">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/GW_flow_trimmed.mp4' | relative_url }}" type="video/mp4">
</video>

<video autoplay loop muted playsinline>
  <source src="{{ '/assets/Dupuit-NN-noise.mp4' | relative_url }}" type="video/mp4">
</video>
</div>
</div>

<div class="project-card">
<h4>Analytical and Numerical Models of Terrestrial Hydrology</h4>

<p class="project-meta">
<b>Advisor:</b>
Marc Hesse (UT Austin)
</p>

<p>
Developed theoretical and numerical models to quantify unsaturated and saturated flow.
</p>

<ul>
<li>Derived analytical scaling laws for drainage dynamics in unconfined groundwater systems</li>
<li>Developed finite-difference solvers for nonlinear diffusion equations</li>
<li>Validated theoretical predictions using analytic solutions and real data</li>
</ul>

<div class="project-media">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/terrestrial_hydrology.mp4' | relative_url }}" type="video/mp4">
</video>
</div>
</div>
</div>

<hr>

<div class="project-category">
<h3>Planetary Hydrology</h3>

<div class="project-card">
<h4>Vadose Zone and Groundwater Systems on Early Mars</h4>

<p class="project-meta">
<b>Collaborators:</b>
Eric Hiatt (UT Austin), Rickbir Bahia (ESA), Eleni Bohacek (ESA), Vilmos Steinmann (Eötvös Loránd University), and Marc Hesse (UT Austin)
</p>

<p>
Developed models for groundwater flow, recharge, and residence times in early Martian crust.
</p>

<ul>
<li>Developed aquifer models on spherical shells incorporating vertical heterogeneity</li>
<li>Quantified vadose-zone residence times and infiltration depths</li>
<li>Linked subsurface hydrology to constraints on early Martian climate evolution</li>
</ul>

<div class="project-media">
<img src="{{ '/assets/MarsInfiltration2025.png' | relative_url }}" alt="Infiltration on early Mars">
</div>
</div>

<div class="project-card">
<h4>Melt Migration in Icy Ocean Worlds</h4>

<p class="project-meta">
<b>Advisor:</b>
Steven Vance (NASA JPL) and Marc Hesse (UT Austin)
</p>

<p>
Developed models for melt transport, hydrothermal circulation, and organic migration through icy ocean-world shells.
</p>

<ul>
<li>Modeled melt transport in viscously compacting ice shells</li>
<li>Tracked organic and thermal transport using tracer-based methods</li>
<li>Derived scaling laws for melt migration and hydrothermal circulation timescales</li>
</ul>

<div class="project-media">
<video autoplay loop muted playsinline>
  <source src="{{ '/assets/impact_melt_video.mp4' | relative_url }}" type="video/mp4">
</video>
</div>
</div>
</div>

<hr>

<div class="project-category">
<h3>Hydrogeochemistry</h3>

<div class="project-card">
<h4>Reactive Transport for CO₂ Removal via Enhanced Weathering</h4>

<p class="project-meta">
<b>Collaborators:</b>
Jacob Jordan (Mati Carbon), Valentina Prigobbe (University of Padova), Yoshiki Kanzaki (Georgia Tech), Noah Planavsky (Yale), Christopher T. Reinhard (Georgia Tech)
</p>

<p>
Developing analytical and numerical models for multicomponent reactive transport in soils for carbon dioxide removal.
</p>

<ul>
<li>Formulated analytical models for multicomponent reactive transport in soil columns</li>
<li>Derived nonlinear wave solutions for cation exchange processes</li>
<li>Validated predictions against PHREEQC geochemical simulations</li>
</ul>

<div class="project-media-wide">
<img src="{{ '/assets/richards_eqns_poster.png' | relative_url }}" alt="Soil as a chromatographic column">
</div>
</div>
</div>

<hr>

<div class="project-category">
<h3>Numerical Methods</h3>

<div class="project-card">
<h4>High-Order Finite-Volume Methods in Curvilinear Coordinates</h4>

<p class="project-meta">
<b>Advisor:</b>
Kun Xu (HKUST)
</p>

<p>
Developed high-order numerical schemes for solving hyperbolic partial differential equations in complex geometries.
</p>

<ul>
<li>Developed fifth-order WENO reconstruction schemes in curvilinear coordinates</li>
<li>Derived analytical weights and verified convergence properties</li>
<li>Implemented and released an open-source numerical solver framework</li>
</ul>

<p class="project-links">
<a href="{{ '/papers/shadab_fifthWENO_CnF_2019.pdf' | relative_url }}" target="_blank">Paper</a> |
<a href="https://github.com/mashadab/WENO-curvilinear" target="_blank">Code</a>
</p>

<div class="project-media-wide">
<iframe src="https://player.vimeo.com/video/524120989?autoplay=1&loop=1&muted=1&background=1" allow="autoplay; fullscreen"></iframe>
</div>
</div>

<div class="project-card">
<h4>High-Performance Scientific Computing for Large-Scale PDEs</h4>

<p class="project-meta">
<b>Platform:</b>
Stampede2, Texas Advanced Computing Center
</p>

<p>
Built and tested scientific computing workflows for solving large-scale partial differential equations.
</p>

<ul>
<li>Implemented C++ solvers and automated testing workflows for elliptic PDE problems</li>
<li>Integrated scientific libraries including PETSc, HDF5, MASA, and GRVY</li>
<li>Used SLURM, Docker, Travis CI, and code-coverage tools for reproducible computation</li>
</ul>

<div class="project-media-wide">
<img src="{{ '/assets/Stampede2.png' | relative_url }}" alt="Solving equations on Stampede2 supercomputer">
</div>

<p class="project-links">
<a href="https://www.youtube.com/watch?v=I4WwXOMeBo4" target="_blank">Video</a>
</p>
</div>
</div>

<hr>

<div class="project-category">
<h3>Fluid Mechanics</h3>

<div class="project-card">
<h4>Drop Dynamics in Viscoelastic Media</h4>

<p class="project-meta">
<b>Advisor:</b>
Irmgard Bischofberger (MIT)
</p>

<p>
Studied the breakup and stability of falling drops in viscoelastic fluids using experiments and image analysis.
</p>

<ul>
<li>Characterized drop breakup and stability in viscoelastic fluids</li>
<li>Quantified Deborah number scaling using controlled experiments</li>
<li>Developed MATLAB tools for high-speed image-based flow analysis</li>
</ul>

<div class="project-media-wide">
<iframe src="https://player.vimeo.com/video/524103920?autoplay=1&loop=1&muted=1&background=1" allow="autoplay; fullscreen"></iframe>
</div>

<p class="project-links">
<a href="https://meetings.aps.org/Meeting/DFD20/Session/S03.3" target="_blank">APS DFD Abstract</a> |
<a href="https://github.com/mashadab/drop-dynamics" target="_blank">Code</a>
</p>
</div>

<div class="project-card">
<h4>Combustion and Multiphysics Flow Modeling</h4>

<p>
Developed models and experiments for reacting flows, high-speed propulsion, and multicomponent combustion.
</p>

<ul>
<li>Analyzed flame stability under varying Lewis number conditions</li>
<li>Simulated reacting flows in high-speed scramjet-like regimes</li>
<li>Coupled thermal, fluid, and chemical transport processes in combustion systems</li>
</ul>

<div class="project-media">
<iframe src="https://player.vimeo.com/video/524147082?autoplay=1&loop=1&muted=1&background=1" allow="autoplay; fullscreen"></iframe>
</div>
</div>
</div>