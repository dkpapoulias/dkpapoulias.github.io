---
layout: page
title: neutrinoSPHERE
description: "<img src='/assets/img/EN-Funded by the EU-POS.jpg' style='height:35px;'>"
img: assets/img/neutrinoSPHERE.png
importance: 1
category: work
related_publications: false
---

<!-- Logos row -->
<div style="position: relative; height: 0; margin-bottom: 0;">
  <a href="https://www.uni-hamburg.de" target="_blank">
    <img id="uhh-logo-project" src="/assets/img/uhh_logo.png" 
         alt="Universität Hamburg" 
         style="height: 100px; position: absolute; top: -110px; left: 150px;">
  </a>
</div>

<script>
  function updateProjectLogo() {
    const theme = document.documentElement.getAttribute('data-theme');
    const logo = document.getElementById('uhh-logo-project');
    if (logo) {
      logo.src = (theme === 'dark') ? '/assets/img/uhh_logo_dark.png' : '/assets/img/uhh_logo.png';
    }
  }
  updateProjectLogo();
  const observer = new MutationObserver(updateProjectLogo);
  observer.observe(document.documentElement, { attributes: true, attributeFilter: ['data-theme'] });
</script>

<div class="row justify-content-center align-items-center mt-1 mb-4">
  <div class="col-sm-5 text-center">
    {% include figure.liquid 
      path="assets/img/neutrinoSPHERE.png" 
      title="neutrinoSPHERE" 
      class="img-fluid"
    %}
  </div>
</div>

<!-- Project Description -->
## About the Research Programme
<p> 
<b>neutrinoSPHERE</b> is a research project funded by the <b>European Commission</b> for the period 2026–2028. It is supported under the <i>HORIZON Europe MSCA Postdoctoral Fellowships</i> – European Fellowships (GA 101198541) and is hosted by the research group of <a href="https://www.physik.uni-hamburg.de/iexp/gruppe-nikolopoulos.html">Prof. K. Nikolopoulos</a> at the <a href="https://www.physik.uni-hamburg.de/iexp.html">Institute of Experimental Physics</a>, as well as the Cluster of Excellence <a href="https://www.qu.uni-hamburg.de/">Quantum Universe</a> at the <a href="https://www.uni-hamburg.de/en.html">University of Hamburg</a>, Germany. 
</p>




## Vision
The neutrinoSPHERE project will advance the state of the art in modern astroparticle physics and open new directions in searches for new physics, aiming to address fundamental long-standing questions on the origin of neutrino masses and the existence of dark matter. It will exploit the ultra-low threshold capability of Spherical Proportional Counters, employed for dark matter searches by the NEWS-G Collaboration, to explore coherent elastic neutrino-nucleus scattering (CEvNS) beyond the Standard Model and dark matter-nucleus signals. To this end, neutrinoSPHERE will employ machine-learning techniques to develop new computational tools for fast and accurate signal reconstruction, incorporating systematic uncertainties.

The project has a duration of 24 months and includes research visits at IFT Madrid and NTUA Athens, where I will collaborate with world-leading experts on machine-learning approaches and connections between astroparticle physics and cosmology.


<div style="margin-top:3rem; margin-bottom:2.5rem;">
  <hr style="width:60%; margin:auto;">
</div>

## neutrinoSPHERE  Results

<div style="margin-bottom:2.5rem;"></div>

<!--  ADD PUBLICATIONS HERE --->


### 📘 Publications

<div class="row mt-3">

<div class="col-md-4 mb-4">
<div class="card h-100 shadow-sm border-0">
<div class="card-body">

<h6 class="card-title" style="color:#1f4fbf;">
Axial-vector neutral-current measurements in coherent elastic neutrino-nucleus scattering experiments
</h6>

<p class="small text-muted mb-2">
D. Aristizabal Sierra, Pablo M. Candela, Valentina De Romeri,
Dimitrios K. Papoulias, Laura Trincado S
</p>

<a href="https://arxiv.org/abs/2603.05281" target="_blank" class="badge bg-danger text-decoration-none">
arXiv:2603.05281
</a>

</div>
</div>
</div>


<div class="col-md-4 mb-4">
<div class="card h-100 shadow-sm border-0">
<div class="card-body">

<h6 class="card-title" style="color:#1f4fbf;">
Testing light and heavy vector mediators with solar CEνNS measurements
</h6>

<p class="small text-muted mb-2">
Valentina De Romeri, Dimitrios K. Papoulias,
Federica Pompa, Gonzalo Sanchez Garcia, Christoph A. Ternes
</p>

<a href="https://arxiv.org/abs/2603.00554" target="_blank" class="badge bg-danger text-decoration-none">
arXiv:2603.00554
</a>

</div>
</div>
</div>


<div class="col-md-4 mb-4">
<div class="card h-100 shadow-sm border-0">
<div class="card-body">

<h6 class="card-title" style="color:#1f4fbf;">
Sensitivity to sub-GeV dark matter in forthcoming spallation-source neutrino experiments
</h6>

<p class="small text-muted mb-2">
D. Aristizabal Sierra, Valentina De Romeri,
Dimitrios K. Papoulias, G. Sanchez García
</p>

<a href="https://arxiv.org/abs/2603.02132" target="_blank" class="badge bg-danger text-decoration-none">
arXiv:2603.02132
</a>

</div>
</div>
</div>

</div>


<!--  ADD TALKS HERE --->

<div style="margin-top:2.5rem;"></div>

### 👨‍🏫 Talks

<div class="list-group list-group-flush mt-3">

<div class="list-group-item">
<b>Project related talks will be listed here</b><br>
<span class="text-muted small">
coming soon...
</span>
</div>



</div>



<!-- Outreach -->

<div style="margin-top:2.5rem;"></div>

### 🌍 Outreach
<div class="list-group list-group-flush mt-3">

<div class="list-group-item">
<b>science communication activities will be reported here</b><br>
<span class="text-muted small">
coming soon...
</span>
</div>



</div>

<!-- EU Disclaimer -->
<div style="margin-top: 3rem; padding: 1rem; border-top: 1px solid #ccc; font-size: 0.85rem; color: #666;">
  Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency (REA). Neither the European Union nor the granting authority can be held responsible for them.
</div>
