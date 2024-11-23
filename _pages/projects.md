---
title: "Projects"
layout: gridlay
sitemap: false
permalink: /projects/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Academic

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Two Phase Flow in a Viscously Compacting Matrix</h4>
  
<b>Advisor:</b>
<i> Professor Marc Hesse, University of Texas at Austin</i>

Developing a 2D solver to simulate two immiscible fluids inside a viscously compacting porous solid. The solver is based on:
* Conservative finite-difference scheme
* Second order in space and theta method in time
* General framework for implementation in other fields

The applications I am currently studying as a part of my doctoral study are:
* Firn densification due to melt percolation and refreezing in glaciers and investigating the effects of global warming
* Melt percolation during core formation in planetesimals (young planets) to understand the mechanism of planetary core formation
* <a href="https://agu.confex.com/agu/fm20/webprogram/Paper712914.html" target="_blank">Groundwater filling times for large impact basins on early Mars and implications for the onset of post impact hydrothermal systems</a>

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524095933?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Investigating Fluid Drainage using Physics Informed Neural Networks</h4>
  
<b>Collaborators:</b>
<i> DingCheng Luo, Yiran Shen, Eric Hiatt, and Prof. Marc Hesse, University of Texas at Austin</i>

Physics Informed Neural Networks (PINNs) is a state-of-the-art tool for finding data-driven solutions to PDEs and discovering parameters in a PDE from
a given data. In the present work, we have studied both, in the context of fluid
drainage from the edge of a porous reservoir.
We are interested in finding
* A steady-state PDE, called Dupuit-Boussinesq approximation, from both synthetic and experimental data
for a range of given input flow values.
* An estimation problem for the transient flow PDE, using numerical solutions from finite-difference simulations as the input data to
infer both the hydraulic conductivity and the outflow boundary condition.
* Difficulties in implementing PINNs for studying this problem, for example, when
the data does not perfectly match the PDEs or scaling of the misfit terms.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524097521?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Suppression of drop breakup in a viscoelastic bath</h4>
  
<b>Advisor:</b>
<i> Professor Irmgard Bischofberger, MIT</i>

A drop of a Newtonian liquid falling in a bath of another, less-dense and miscible, Newtonian liquid, deforms into a torus which is either stable or subsequently fragments into smaller structures, depending on the relative contributions of diffusive, viscous and convective forces. 
Here we show that the <a href="https://meetings.aps.org/Meeting/DFD20/Session/S03.3" target="_blank">dynamics of the drop can change significantly when the bath is replaced by a viscoelastic liquid</a>. Wrote a MATLAB code (<a href="https://github.com/mashadab/drop-dynamics" target="_blank">src</a>) to analyse a moving frame video.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524103920?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> High-Order Finite-Volume Reconstruction in Curvilinear Coordinates</h4>
  
<b>Advisor:</b>
<i> Professor Kun Xu, The Hong Kong University of Science and Technology</i>

High-order reconstruction represents the state-of-the-art computational physics. The main ideas in using <a href="https://users.soe.ucsc.edu/~dongwook/wp-content/uploads/2019/ams260/_build/html/_downloads/Shu_wenoConvection_2009.pdf" target="_blank">Weighed Essentially Non-Oscillatory schemes</a> to solve various hyperbolic PDEs and other convection dominated problems, and present a collection of applications in areas including computational fluid dynamics, computational astronomy and astrophysics, semiconductor device simulation, traffic flow models, computational biology and some non-PDE applications.
Research highlights:
* Proposed <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_fifthWENO_CnF_2019.pdf" target="_blank">fifth order finite volume WENO-C in orthogonally-curvilinear coordinates</a>.
* WENO-Curvilinear reconstruction and averaging weights provided for standard grids (<a href="https://github.com/mashadab/WENO-curvilinear" target="_blank">src</a>).
* Analytical values of weights for Radius → ∞ case conform to conventional WENO-JS.
* Tests performed in <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_ICOSAHOM_2020.pdf" target="_blank">curvilinear coordinates</a> testify for fifth order & ENO properties.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524120989?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Solving Heat Equation using High-order Methods on Stampede2 Supercomputer</h4>
  
<b>Instructor:</b>
<i> Professor Karl Schulz, University of Texas at Austin</i>

Used Stampede2 supercomputer at Texas Advanced Computing Center to solve the steady-state heat equation in 1D and 2D. 
Built and ran the C++ codes, bash scripts using SLURM Workload Manager. Perform code testing mainly verification, regression and runtime performance testing. 
Libraries used:
* GRVY for timekeeping and debugging
* MASA for method of manufactured solutions
* Bash automated testing system (bats) for designing regression tests
* gcov and lcov for code coverage
* Hierarchical Data Formatting (HDF5) for output file formatting
* Portable Extensible Toolkit for Scientific Computation (PETSc) library with GMRES solver integration
* Travis CI for continuous integration
* Docker for containerization

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524167291?autoplay=0&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Investigation and Control of Unstart Phenomenon in Scramjets</h4>
  
<b>Advisor:</b>
<i> Professor M.F. Baig, Aligarh Muslim University, India</i>

Engine unstart refers to the transient disgorging, which is generated with the aid of thermal choking due to impulsive heat addition inside the combustor. The generated pressure disturbance traverses upstream
inside the isolator duct in the form of normal shock, resulting in a loss of thrust and possible flameout of the engine.
Research highlights:
* Designed a Scramjet based on different operating Mach numbers
* A quasi-one-dimensional adaptation of mass, momentum and energy conservation.
* A <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_Scramjet_2017.pdf" target="_blank">single-input-single-output (SISO) mechanism</a> based on pressure feedback is proposed to avert Engine unstart

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524139367?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4> Effective Lewis Number for Multicomponent Hydrocarbon-Air Mixtures</h4>
  
<b>Advisor:</b>
<i> Professor M.R. Ravi, Indian Institute of Technology, Delhi, India</i>

* Analyzed combustion characteristics of methane and natural gas mixtures with varying hydrogen blending.
* Performed the experiments using constant pressure combustion chamber apparatus with Schlieren imaging.
* Simulated the corresponding flames in 1D on CHEMKIN using PREMIX module.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524147082?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0"></iframe>
</div>
</div>
</div>


## Industrial

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Hummingbird – Wearable Device for Exchanging Information</h4>
  
<b>Co-Founders:</b>
<i> Sal Amarsinghe, Mohammad Afzal Shadab, Dr. Nikhil Bhargava, Melody Mui and Dakota Pierce, MIT and Hong Kong Innovation Node</i>

* Ideated and validated consumer problems and B2B market opportunities through market research.
* Designed prototype on AutoCAD, fabricated using 3D printing, and implemented fast & accurate algorithms.
* Received MIT Sandbox Innovation Fund worth $5000 and won both Judge’s & Audience Awards at MIT
Entrepreneurship and Maker Skills Integrator program (2018).

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524151731?autoplay=0&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Industrial Compressors and Gas Turbines</h4>
  
<b>Summer Internship Supervisor:</b>
<i> Ramray Tudu, Deputy General Manager, Gas Authority of India Limited</i>

* Worked at a C2C3 plant at GAIL, participating in its pre-commissioning and commissioning testing.
* Studied the working of several industrial compressors and a gas turbine (Siemens SGT700).

</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Formula Student Race Car and Hybrid Tricycle</h4>
  
<b>Technical Member & Team Lead:</b>
<i> Society of Automotive Engineers, Aligarh Chapter</i>

* Conceptualized ergonomically designed the vehicles with improved aerodynamic performance.
* Designed the vehicles on AutoCAD, simulated on ANSYS, and then finally fabricated.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524157097?autoplay=0&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

## Hobby

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4>Dimensional Analysis tool using Pi Theorem</h4>

<b>Developer:</b>
<i> Mohammad Afzal Shadab</i>

The Python GUI based tool can perform the dimensional analysis using Buckingham Pi theorem (<a href='https://drive.google.com/drive/folders/1-BnQePbN60gHgodgULoHO3ArwdrybHyl' target='_blank'>exe</a>/<a href='https://github.com/mashadab/dimensional-analysis' target='_blank'>src</a>) with Youtube tutorial.
The tool can find the number of the repeating variables and also the linear dependence in between them.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524159648?autoplay=0&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
<h4>Twitter Webscraper</h4>

<b>Developer:</b>
<i> Mohammad Afzal Shadab</i>

Salient features of the Python program (<a href='https://github.com/mashadab/twitterwebscraper' target='_blank'>src</a>):

* Calculates and can also print Tweets with a "keyword" for a specific period in a specific region in the world.
* Doesn't require Twitter Official Access Token.
* Bypasses Twitter official time limit of 7 days.
