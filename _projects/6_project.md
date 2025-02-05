---
layout: page
title: unsteady flows
description:
img: assets/img/naca_fra.gif
importance: 4
category: interested
---

<style>
  .top-one {
     margin-top: 1cm;
  }
</style>

<!-- <h3> Supervisor: Dr. <a href="https://me.queensu.ca/People/Piomelli/"> Ugo Piomelli</a> <sup> 1 </sup> </h3>

<h3> Collaborators: Dr. <a href="https://www.bsc.es/research-development/research-areas/engineering-simulations/alya-high-performance-computational"> Oriol Lehmkuhl </a> <sup> 2 </sup> and
Dr. <a href="https://www.bsc.es/miro-jane-arnau"> Arnau Miro </a> <sup> 3 </sup> </h3> -->

<!-- <p class="top-one"> </p> -->

<h4 class="content"><span> CFD code: </span> <a href="https://www.bsc.es/research-development/research-areas/engineering-simulations/alya-high-performance-computational"> Alya </a> </h4>
<h4 class="content"><span> Resources: </span>  Compute Canada (Niagara/Mist Cluster)</h4>

<!-- <p class="top-one"> <sup> 1 </sup> Professor, Mechanical Engineering, Queen's University, Kingston, Canada <br>
<sup> 2 </sup> Group Leader, Large-scale turbulence simulation, Barcelona Supercomputing Center (BSC), Spain <br>
<sup> 3 </sup> Postdoctoral researcher, Large-scale turbulence simulation, Barcelona Supercomputing Center (BSC), Spain
</p> -->

<hr>

<p class="top-one"> </p>

<h2 class="content"><span> Rod-Airfoil and pitching airfoil configurations </span> </h2>

<p class="top-one"> </p>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/video.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/naca_fra.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <b> <i> left panel </i> </b>:  interaction of Karman vortices with evolution of boundary layer on NACA0012;
    <i> top) </i> span-averaged streamwise velocity non-dimensionalized by incoming free-stream velocity, \(\langle u \rangle /U_o\); blue: -0.1, red: 2.0;  
    <i> bottom) </i> non-dimensionalized turbulent kinetic energy \(\langle u'_iu'_i \rangle /U_o^2\);white: 0.0, red: 0.15;
    <br>
    <b> <i> right panel </i> </b>: effect of constant pitching motion on flow field of NACA0012; span-averaged spanwise vorticity, \(\Omega_z c /U_o\); blue: -20.0, red: 20.0
</div>


<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %} -->
