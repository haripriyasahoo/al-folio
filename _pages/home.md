---
layout: home
title: Home
permalink: /home/
nav: true
nav_order: 7
news: false # includes a list of news items
latest_posts: false # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
 <style>
       body{
    overflow-x:hidden
}
.pics{
/*     width:100vw; */
    height:50vh
}

.carousel-inner{
    padding-bottom: 2vh;
    max-width:100%;

}
.carousel-dark .carousel-control-next-icon,.carousel-dark .carousel-control-prev-icon{
    filter:invert(0) greyscale(0);
}
 .carousel-indicators{
    bottom: 4vh;
     z-index:12;
} 
 .carousel .carousel-control-next-icon{
    width:40px;
     height:40px;
     color:white;
}
.carousel-caption p{
                color:white;
          }
.carousel .carousel-control-prev-icon{
    width:40px;
    height:40px;
    color:white;
} 
    </style>
<div id="carouselExampleDark" class="carousel carousel-dark slide">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active" data-bs-interval="10000">
          <img class="pics" src="../assets/img/1.jpg" class="d-block w-100"  alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>First slide label</h5>
            <p>Some representative placeholder content for the first slide.</p>
          </div>
        </div>
        <div class="carousel-item" data-bs-interval="2000">
          <img class="pics" src="../assets/img/2.jpg" class="d-block w-100"  alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Second slide label</h5>
            <p>Some representative placeholder content for the second slide.</p>
          </div>
        </div>
        <div class="carousel-item">
          <img class="pics" src="../assets/img/3.jpg" class="d-block w-100"  alt="...">
          <div class="carousel-caption d-none d-md-block">
            <h5>Third slide label</h5>
            <p>Some representative placeholder content for the third slide.</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden"></span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden"></span>
      </button>
    </div>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

Welcome to Marine Aero- & Hydrodynamics Laboratory led by <a href="/pi/">Dr. Asim Önder</a> at <a href="https://maev.nsysu.edu.tw/?Lang=en">Department of Marine Environment and Engineering</a> of <a href="https://www.nsysu.edu.tw/">National Sun Yat-sen University</a>. The lab pursues innovative fluid mechanics and CFD research to solve geophysical and engineering problems involving complex multi-phase, multi-scale flows in the marine environment.

The current research interests include:
- <b> Air-sea interactions</b>: wind-wave interactions, Langmuir circulations, gas and heat exchange
- <b> Offshore wind energy </b>: metocean characterization, aero-hydro coupling, atmospheric-stability effects, land-sea transition
- <b> Tsunamis </b>: bottom friction, sediment transport
- <b> Oceanic/atmospheric turbulence</b>: large-eddy simulation of near-surface layers, Reynolds-stress modelling, non-equilibrium turbulence
- <b> Computational science </b>: machine-learning models for interfacial flows, adjoint methods, immersed boundary methods, adaptive methods

