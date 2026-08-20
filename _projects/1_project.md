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

The project has a duration of 24 months and includes research visits at IFT Madrid and NTUA Athens, where I will collaborate with world-leading experts on machine-learning approaches and connections between astroparticle physics and cosmology.

<div style="margin-top:3rem; margin-bottom:2.5rem;">
  <hr style="width:60%; margin:auto;">
</div>

## neutrinoSPHERE Results

<div style="margin-bottom:2.5rem;"></div>

<!--  ADD PUBLICATIONS HERE --->

### 📘 Publications

<div class="mt-4">

<!-- Paper 1 -->
<div class="mb-5 pb-4 border-bottom">

<h5>
Axial-vector neutral-current measurements in coherent elastic neutrino-nucleus scattering experiments
</h5>

<p class="small text-muted">
D. Aristizabal Sierra, Pablo M. Candela, Valentina De Romeri,
Dimitrios K. Papoulias, Laura Trincado S.
</p>

<div class="row align-items-center mt-3">
  <div class="col-md-4 mb-3 mb-md-0 text-center">
    <img src="/assets/img/neutrinoSPHERE/axial_gA.png"
         alt="Projected sensitivity to the axial coupling gA"
         class="img-fluid"
         style="max-height: 220px; width: auto;">
  </div>

  <div class="col-md-8">
    <p>
      The usually subleading axial-vector contribution to CEνNS becomes experimentally accessible with suitable spinful targets. Fluorine-based detectors, particularly C₃F₈, offer especially strong sensitivity, with future reactor and spallation-source measurements potentially determining the axial coupling \(g_A\) at the \(\mathcal{O}(10\%)\) level under favorable threshold and flux uncertainties.
    </p>

    <a href="https://doi.org/10.1103/cc36-6r2g"
       target="_blank"
       class="badge bg-primary text-decoration-none me-1">
      Phys. Rev. D 114, 033003
    </a>

    <a href="https://arxiv.org/abs/2603.05281"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2603.05281
    </a>

  </div>
</div>

</div>

<!-- Paper 2 -->
<div class="mb-5 pb-4 border-bottom">

<h5>
Testing light and heavy vector mediators with solar CEνNS measurements
</h5>

<p class="small text-muted">
Valentina De Romeri, Dimitrios K. Papoulias,
Federica Pompa, Gonzalo Sanchez Garcia, Christoph A. Ternes
</p>

<div class="row align-items-center mt-3">
  <div class="col-md-4 mb-3 mb-md-0 text-center">
    <img src="/assets/img/neutrinoSPHERE/NSI_2D.png"
         alt="Constraints on new vector neutrino interactions"
         class="img-fluid"
         style="max-height: 220px; width: auto;">
  </div>

  <div class="col-md-8">
    <p>
      The first solar CEνNS measurements from XENONnT, PandaX-4T and LZ provide a new probe of vector interactions beyond the Standard Model. Their combination constrains both effective non-standard interactions and light-mediator scenarios, reaching sensitivity competitive with dedicated neutrino-scattering experiments in parts of the parameter space.
    </p>

    <span class="badge bg-primary me-1">
      Accepted in JCAP
    </span>

    <a href="https://arxiv.org/abs/2603.00554"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2603.00554
    </a>

  </div>
</div>

</div>

<!-- Paper 3 -->
<div class="mb-5 pb-4 border-bottom">

<h5>
Sensitivity to sub-GeV dark matter in forthcoming spallation-source neutrino experiments
</h5>

<p class="small text-muted">
D. Aristizabal Sierra, Valentina De Romeri,
Dimitrios K. Papoulias, G. Sanchez García
</p>

<div class="row align-items-center mt-3">
  <div class="col-md-4 mb-3 mb-md-0 text-center">
    <img src="/assets/img/neutrinoSPHERE/sub-GeV_DM.png"
         alt="Projected sub-GeV dark matter sensitivity at spallation sources"
         class="img-fluid"
         style="max-height: 220px; width: auto;">
  </div>

  <div class="col-md-8">
    <p>
      Forthcoming CEνNS experiments at ESS, J-PARC and CSNS can simultaneously serve as sensitive searches for sub-GeV dark matter produced at spallation sources. Detailed production and detector simulations reveal previously unexplored parameter space, with several experimental configurations reaching the thermal-relic target in the tens-of-MeV mass range.
    </p>

    <a href="https://doi.org/10.1007/JHEP07(2026)220"
       target="_blank"
       class="badge bg-primary text-decoration-none me-1">
      JHEP 07 (2026) 220
    </a>

    <a href="https://arxiv.org/abs/2603.02132"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2603.02132
    </a>

  </div>
</div>

</div>

<!-- Paper 4 -->
<div class="mb-5 pb-4 border-bottom">

<h5>
Refined extraction of electroweak and nuclear parameters from germanium CEνNS data
</h5>

<p class="small text-muted">
Valentina De Romeri, Laura Duque, Dimitrios K. Papoulias,
G. Sanchez Garcia, Christoph A. Ternes
</p>

<div class="row align-items-center mt-3">
  <div class="col-md-4 mb-3 mb-md-0 text-center">
    <img src="/assets/img/neutrinoSPHERE/COH-Ge.png"
         alt="Combined COHERENT-Ge and CONUS+ parameter constraints"
         class="img-fluid"
         style="max-height: 220px; width: auto;">
  </div>

  <div class="col-md-8">
    <p>
      The complementary neutrino energies of COHERENT-Ge and CONUS+ allow nuclear, electroweak and detector-response effects to be disentangled in a joint analysis. Their combination improves the extraction of the germanium neutron radius and neutron skin while simultaneously providing information on the weak mixing angle and nuclear quenching response.
    </p>

    <a href="https://doi.org/10.1007/JHEP08(2026)077"
       target="_blank"
       class="badge bg-primary text-decoration-none me-1">
      JHEP 08 (2026) 077
    </a>

    <a href="https://arxiv.org/abs/2605.27121"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2605.27121
    </a>

  </div>
</div>

</div>

<!-- Paper 5 -->
<div class="mb-4">

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

    <a href="https://arxiv.org/abs/2607.24584"
       target="_blank"
       class="badge bg-danger text-decoration-none">
      arXiv:2607.24584
    </a>

  </div>
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
