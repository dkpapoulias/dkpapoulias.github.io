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
<p> 
<b>neutrinoSPHERE</b> is a research project funded by the <b>European Commission</b> for the period 2026–2028. It is supported under the <i>HORIZON Europe MSCA Postdoctoral Fellowships</i> – European Fellowships (GA 101198541) and is hosted by the research group of <a href="https://www.physik.uni-hamburg.de/iexp/gruppe-nikolopoulos.html">Prof. K. Nikolopoulos</a> at the <a href="https://www.physik.uni-hamburg.de/iexp.html">Institute of Experimental Physics</a>, as well as the Cluster of Excellence <a href="https://www.qu.uni-hamburg.de/">Quantum Universe</a> at the <a href="https://www.uni-hamburg.de/en.html">University of Hamburg</a>, Germany. 
</p>

## Vision
The neutrinoSPHERE project will advance the state of the art in modern astroparticle physics and open new directions in searches for new physics, aiming to address fundamental long-standing questions on the origin of neutrino masses and the existence of dark matter. It will exploit the ultra-low threshold capability of Spherical Proportional Counters, employed for dark matter searches by the NEWS-G Collaboration, to explore coherent elastic neutrino-nucleus scattering (CEvNS) beyond the Standard Model and dark matter-nucleus signals. To this end, neutrinoSPHERE will employ machine-learning techniques to develop new computational tools for fast and accurate signal reconstruction, incorporating systematic uncertainties.

The project has a duration of 24 months and includes research visits at IFT Madrid and NTUA Athens, where I will collaborate with world-leading experts on machine-learning approaches and connections between astroparticle physics and cosmology.

<!-- EU Disclaimer -->
<div style="margin-top: 3rem; padding: 1rem; border-top: 1px solid #ccc; font-size: 0.85rem; color: #666;">
  Funded by the European Union. Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the European Union or the European Research Executive Agency (REA). Neither the European Union nor the granting authority can be held responsible for them.
</div>
