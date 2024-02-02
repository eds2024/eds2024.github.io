---
layout: page
title: What is ELLIS?
permalink: /
---

The [European Laboratory for Learning and Intelligent Systems (ELLIS)](https://ellis.eu/) is a pan-European AI network of excellence which focuses on fundamental science, technical innovation and societal impact. Founded in 2018, ELLIS builds upon machine learning as the driver for modern AI and aims to secure Europe’s sovereignty in this competitive field by creating a multi-centric AI research laboratory. ELLIS has established 41 units in 16 different countries in Europe. It has also launched the [ELLIS PhD Program](https://ellis.eu/phd-postdoc), one of Europe’s most competitive PhD programs which aims to foster and educate the best talent in machine learning and related research areas by pairing outstanding students with leading academic and industrial researchers across Europe. The ELLIS PhD Program has received funding from the European Union’s Horizon research and innovation programme under [ELIAS](https://elias-ai.eu/) Grant Agreement No. 101120237 (2023-2027) and from the Horizon Europe research and innovation programme under [ELISE](https://www.elise-ai.eu/) Grant Agreement No. 951847 (2020 – 2024).

# What is EDS2024?

<section class="center-section">
  <div class="carousel">
    <div class="carousel-container" id="carouselContainer">
      <!--<div class="carousel-item"><img alt="" src="https://www.sorbonne-universite.fr/sites/default/files/styles/2400xauto/public/media/2020-01/couvent-cordeliers.jpg"></div> REMOVED AS RESOLUTION TOO LOW-->
      <div class="carousel-item"><img alt="" src="https://www.sorbonne-universite.fr/sites/default/files/styles/1536xauto/public/media/2020-01/CDL_Cloitre_galerie_2.JPEG"></div>
      <div class="carousel-item"><img alt="" src="https://www.sorbonne-universite.fr/sites/default/files/styles/1536xauto/public/media/2020-01/CDL_Cloitre_jardin.JPEG"></div>
      <div class="carousel-item"><img alt="" src="https://www.sorbonne-universite.fr/sites/default/files/styles/1536xauto/public/media/2020-01/CDL_Amphi_Farabeuf.JPEG"></div>
      <div class="carousel-item"><img alt="" src="https://www.polytechnique.edu/fondation/sites/fondation/files/styles/contenu_detail/public/content/actualites/images/2022-03/InnovationPark.jpg"></div>
      <!-- Add more slides as needed -->
    </div>
  </div>
</section>
<script>
  let currentIndex = 0;
  const intervalTime = 5000; // Adjust the interval time in milliseconds

  const carouselContainer = document.getElementById('carouselContainer');
  const totalSlides = document.querySelectorAll('.carousel-item').length;

  function nextSlide() {
    currentIndex = (currentIndex + 1) % totalSlides;
    updateCarousel();
  }

  function updateCarousel() {
    const translateValue = -currentIndex * 100 + '%';
    carouselContainer.style.transform = 'translateX(' + translateValue + ')';
  }

  setInterval(nextSlide, intervalTime);
</script>

The ELLIS Doctoral Symposium is an annual conference for [ELLIS PhD students](https://ellis.eu/phd-postdoc) and other PhD students to meet in person and share knowledge about machine learning. The ELLIS Doctoral Symposium 2024 (EDS2024) is the fourth edition, which is co-organised by the University of Tübingen and the Institut Polytechnique de Paris, and will be held in Paris, France. It is expected to host 150 attendees during one week from **Monday, August 26 - to Friday, August 30**. 

The focus of this year’s symposium is **AI & Sustainability**.

Participants are expected to prepare a poster or a tooling session with a strong machine learning component. **The topic of the poster or tooling session is completely open**, as the [ELLIS Programs](https://ellis.eu/programs) bring together researchers from multiple disciplines within the machine learning community (Computer Vision, NLP, Theoretical ML, Reinforcement Learning, Human-Centric ML…). 
If upon registering you are unsure about the material you wish to present, do feel free to submit a tentative title.
EDS2024 follows in the footsteps of the previous EDS iterations held in [Helsinki](https://fcai.fi/eds2023/home) (EDS2023), [Alicante](https://ellisalicante.org/eds2022/) (EDS2022) and Tübingen (EDS2021). 
Save the date and join us for **keynotes, poster & tooling sessions** and **social events** in the beautiful City of Light!

Students requiring a short-stay visa for the event can apply [here](https://www.france-visas.gouv.fr/en/web/france-visas/home).
