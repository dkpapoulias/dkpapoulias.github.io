---
layout: about
title: about
permalink: /

subtitle: >
  <a href="https://www.physik.uni-hamburg.de/iexp/gruppe-nikolopoulos/personen/papoulias-dimitrios.html">
    Institute of Experimental Physics, University of Hamburg, Germany
  </a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false
  more_info: |
    <div class="about-profile-logo">
      <a href="https://www.uni-hamburg.de" target="_blank" rel="noopener noreferrer">
        <img id="uhh-logo" src="/assets/img/uhh_logo.png" alt="Universität Hamburg">
      </a>
    </div>
    <script>
      function updateLogo() {
        const theme = document.documentElement.getAttribute('data-theme');
        const logo = document.getElementById('uhh-logo');
        if (logo) {
          logo.src = (theme === 'dark')
            ? '/assets/img/uhh_logo_dark.png'
            : '/assets/img/uhh_logo.png';
        }
      }
      updateLogo();
      const observer = new MutationObserver(updateLogo);
      observer.observe(document.documentElement, {
        attributes: true,
        attributeFilter: ['data-theme']
      });
    </script>

social: false

announcements:
  enabled: true
  scrollable: true
  limit: 5
---

I am a theoretical astroparticle physicist and **Marie Skłodowska-Curie Fellow** at the University of Hamburg, working in the group of [Prof. K. Nikolopoulos](https://www.physik.uni-hamburg.de/iexp/gruppe-nikolopoulos.html).

My research lies at the interface of **neutrino physics, dark matter, and nuclear theory**, with a particular focus on low-energy probes of fundamental physics. My work spans coherent elastic neutrino–nucleus scattering (CEvNS), dark matter direct detection and the neutrino fog, neutrino properties and interactions beyond the Standard Model, light dark sectors and axion-like particles (ALPs), and nuclear structure for neutrino and dark matter searches.

[**Explore my research →**](/research/)

Previously, I held postdoctoral positions in Spain and Greece. For further details on my academic background, see my [Curriculum Vitae](/cv/).