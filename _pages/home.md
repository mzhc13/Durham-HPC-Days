---
layout: splash
permalink: /
hidden: true

header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/background-hpc-days.png
---

<style>
/* === GENERAL === */
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
  background-color: #f9f9f9;
  color: #222;
  scroll-behavior: smooth;
}

h1, h2, h3 {
  font-weight: 600;
}

a {
  color: #0055aa;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}



/* === HERO VIDEO SECTION WITH PARALLAX === */
.hero {
  position: relative;
  width: 100%;
  height: 600px; /* altura de la franja parallax */
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
}

.hero video {
  position: absolute; /* video fijo para parallax */
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1; /* detrás de todo el contenido */
}

.hero::before {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.5); /* overlay para contraste */
  z-index: 0;
}

.hero-content {
  position: relative;
  z-index: 1;
  animation: fadeIn 2s ease-out;
}

.hero-content h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.hero-content p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

.btn {
  background: #0055aa;
  color: white;
  padding: 0.9rem 2rem;
  border-radius: 30px;
  font-weight: 500;
  text-decoration: none;
  transition: all 0.3s ease;
}

.btn:hover {
  background: #003d80;
  transform: translateY(-3px);
}

/* === SECTION STYLING === */
section {
  max-width: 900px;
  margin: 5rem auto;
  padding: 0 1.5rem;
  text-align: center;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

section p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #444;
}

/* === IMAGE GRID === */
.image-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1rem;
  margin-top: 2rem;
}

.image-grid img {
  width: 100%;
  height: 220px;
  object-fit: cover;
  border-radius: 10px;
  transition: transform 0.4s ease, box-shadow 0.4s ease;
}

.image-grid img:hover {
  transform: scale(1.05);
  box-shadow: 0 8px 16px rgba(0,0,0,0.3);
}

/* === FADE-IN EFFECT === */
.fade-in {
  opacity: 0;
  transform: translateY(40px);
  transition: all 0.8s ease-out;
}

.fade-in.visible {
  opacity: 1;
  transform: translateY(0);
}

/* === FOOTER NOTE === */
.footer-note {
  text-align: center;
  padding: 2rem 0;
  background: #003366;
  color: white;
  font-size: 0.9rem;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(40px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>



<!-- === ABOUT SECTION === -->
<section id="about" class="fade-in">
  <h2>💡 About the Event</h2>
  <p>
    The <strong>Durham HPC Days</strong> bring together researchers, developers, and practitioners 
    to explore the frontiers of high-performance computing, data analysis, and scientific innovation.
  </p>
</section>


<!-- === HEADER IMAGE === -->
<div class="header-image"></div>

<!-- === HERO VIDEO SECTION CON PARALLAX === -->
<div class="hero">
  <video autoplay muted loop playsinline>
    <source src="/assets/images/video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <div class="hero-content">
    <h1>Durham HPC Days 2025 Video Recap</h1>
    <p>Take a look back at Durham HPC Days 2025 in this short recap featuring our keynote speakers</p>
    <a href="/programme/" class="btn">View Programme</a>
  </div>
</div>



<div class="footer-note">
  © 2025 Durham University · Durham HPC Days
</div>


<!-- === GALLERY SECTION === -->
<section id="gallery" class="fade-in">
  <h2>📸 Gallery</h2>
  <div class="image-grid">
    <img src="Durham-HPC-Days/assets/images/cathedral-river-durham.jpeg" alt="River in Durham">
    <img src="/assets/images/cathedral-river-durham.jpeg" alt="Computer Science Building">
      </div>
</section>

<!-- === CONTACT SECTION === -->
<section id="contact" class="fade-in">
  <h2>📬 Get in Touch</h2>
  <p>
    For questions or collaboration opportunities, contact us at  
    <a href="mailto:organisers@durham.ac.uk">organisers@durham.ac.uk</a>.
  </p>
</section>




<script>
  // Fade-in animation on scroll
  document.addEventListener("scroll", function() {
    document.querySelectorAll('.fade-in').forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) {
        el.classList.add('visible');
      }
    });
  });
</script>


