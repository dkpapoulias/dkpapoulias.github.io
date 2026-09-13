---
layout: page
title: neutrinoSPHERE
description: "<img src='/assets/img/EN-Funded by the EU-POS.jpg' style='height:35px; width:auto; object-fit:contain;'>"
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

> **neutrinoSPHERE** is a research project funded by the <b>European Commission</b> for the period 2026–2028. It is supported under the <i>HORIZON Europe MSCA Postdoctoral Fellowships</i> – European Fellowships (GA 101198541) and is hosted by the research group of <a href="https://www.physik.uni-hamburg.de/iexp/gruppe-nikolopoulos.html">Prof. K. Nikolopoulos</a> at the <a href="https://www.physik.uni-hamburg.de/iexp.html">Institute of Experimental Physics</a>, as well as the Cluster of Excellence <a href="https://www.qu.uni-hamburg.de/">Quantum Universe</a> at the <a href="https://www.uni-hamburg.de/en.html">University of Hamburg</a>, Germany.

## Vision

The neutrinoSPHERE project will advance the state of the art in modern astroparticle physics and open new directions in searches for new physics, aiming to address fundamental long-standing questions on the origin of neutrino masses and the existence of dark matter. It will exploit the ultra-low threshold capability of Spherical Proportional Counters, employed for dark matter searches by the NEWS-G Collaboration, to explore coherent elastic neutrino-nucleus scattering (CEvNS) beyond the Standard Model and dark matter-nucleus signals. To this end, neutrinoSPHERE will employ machine-learning techniques to develop new computational tools for fast and accurate signal reconstruction, incorporating systematic uncertainties.

The project has a duration of 24 months and includes **research visits to IFT-UAM/CSIC in Madrid and NTUA Athens**, where I will collaborate with **Prof. David G. Cerdeño** and **Prof. Chris Kouvaris**, respectively. These exchanges will strengthen the project through complementary expertise in dark matter and neutrino phenomenology, machine-learning approaches, and connections between astroparticle physics and cosmology.

<div style="margin-top:3rem; margin-bottom:2.5rem;">
  <hr style="width:60%; margin:auto;">
</div>

## neutrinoSPHERE Results

<div style="margin-bottom:2.5rem;"></div>


<!-- Paper 5 -->

<div class="mb-5 pb-4 border-bottom">

<h5>
Invisible decay of solar neutrinos at dark matter experiments
</h5>

<p class="small text-muted">
Martina Beccaria, Veronica Beligotti, Valentina De Romeri,
Giulia Pagliaroli, Dimitrios K. Papoulias,
Federica Pompa, Christoph A. Ternes
</p>

<div class="row align-items-center mt-3">

  <div class="col-md-4 mb-3 mb-md-0 text-center">

    <img src="/assets/img/neutrinoSPHERE/Invisible_neutrino_decay.png"
         alt="Current and projected constraints on invisible solar-neutrino decay"
         class="img-fluid"
         style="max-height: 220px; width: auto;">

  </div>

  <div class="col-md-8">

    <p>
      Solar-neutrino signals in dark matter detectors provide a new way to search for invisible neutrino decay. The first CEνNS-based constraint, obtained from XENONnT, PandaX-4T and LZ, is already competitive with dedicated solar-neutrino measurements, while future xenon experiments could improve existing limits by up to two orders of magnitude through low-energy neutrino–electron scattering.
    </p>

    <span class="badge bg-primary me-1">
      Accepted in JCAP
    </span>

    <a href="https://arxiv.org/abs/2607.24584"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2607.24584
    </a>

  </div>

</div>

</div>


<!-- Paper 6 -->

<div class="mb-4">

<h5>
Can elastic neutrino scattering account for the LZ230616 event?
</h5>

<p class="small text-muted">
Ayan Chattaraj, Anirban Majumdar,
Dimitrios K. Papoulias, Rahul Srivastava
</p>

<div class="row align-items-center mt-3">

  <div class="col-md-4 mb-3 mb-md-0 text-center">

    <img src="/assets/img/neutrinoSPHERE/LZpaper.png"
         alt="Elastic neutrino interpretation of the LZ230616 event"
         class="img-fluid"
         style="max-height: 220px; width: auto;">

  </div>

  <div class="col-md-8">

    <p>
      Elastic neutrino–xenon scattering cannot explain the isolated LZ230616 high-energy nuclear-recoil event. Standard astrophysical neutrinos, light scalar and vector mediators, neutrinos from dark matter annihilation or decay, and neutrinos from primordial-black-hole evaporation all either fail kinematically or require normalizations that would strongly overproduce lower-energy recoils. Existing constraints independently exclude the required parameter regions.
    </p>

    <a href="https://arxiv.org/abs/2609.10504"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2609.10504
    </a>

  </div>

</div>

</div>

<!--  ADD TALKS HERE --->

### 🎤 Talks

<div class="list-group list-group-flush mt-3">

<div class="list-group-item">
<b>Sub-GeV Dark Matter Searches at Spallation Neutron Sources</b><br>
<span class="text-muted small">
Identification of Dark Matter 2026 (IDM 2026), Zaragoza, Spain — 3 June 2026
</span><br>
<a href="https://indico.capa.unizar.es/event/40/contributions/875/" target="_blank">
Talk information and slides
</a>
</div>

<div class="list-group-item">
<b>Testing light and heavy vector mediators with solar CEνNS measurements</b><br>
<span class="text-muted small">
HEP 2026, Athens, Greece — 9 July 2026
</span><br>
<a href="https://indico.cern.ch/event/1654737/contributions/7165256/" target="_blank">
Talk information and slides
</a>
</div>

<div class="list-group-item">
<b>Refined extraction of electroweak and nuclear parameters from germanium CEνNS data</b><br>
<span class="text-muted small">
Magnificent CEνNS 2026, Heidelberg, Germany — 15 July 2026
</span><br>
<a href="https://plan.events.mpg.de/event/603/contributions/3530/" target="_blank">
Talk information and slides
</a>
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
