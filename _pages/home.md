---
layout: splash
permalink: /
hidden: true
header:
  overlay_image: "/Durham-HPC-Days/assets/images/background-hpc-days.png"
---

<style>
/* === GENERAL === */
body {
  margin: 0;
  font-family: 'Inter', sans-serif;
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


/* hero full-bleed exacto */
.hero {
  position: relative;
  width: 100vw;
  left: 50%;
  right: 50%;
  margin-left: -50vw;
  margin-right: -50vw;
  height: 60vh;          
  min-height: 320px;
  overflow: hidden;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #f9f9f9;
}

#yt-player-wrap {
  position: absolute;
  inset: 0;               /
  overflow: hidden;
  z-index: -1;
}

#yt-player iframe {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100vw;           
  height: 56.25vw;        /* 16:9 height based on vw */
  min-height: 100%;       /
  min-width: 177.78vh;    
  max-width: none;
  max-height: none;
  pointer-events: none;
}
/* superposición oscura */
.hero::before {
  content: "";
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.5);
  z-index: 0;
}

.hero-content {
  position: relative;
  z-index: 1;
  animation: fadeIn 2s ease-out;
  padding: 0 1rem;
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
  background: #002A41;
  color: white;
  padding: 0.9rem 2rem;
  border-radius: 30px;
  font-weight: 500;
  text-decoration: none;
  transition: all 0.3s ease;
  display: inline-block;
  margin: 0.25rem;
}

.btn:hover {
  background: #003d80;
  transform: translateY(-3px);
}

/* === SECTION STYLING === */
section {
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1.5rem;
  text-align: center;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  line-height: 0.3;
}

section p {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #ffff;
}

section t {
  font-size: 0.9rem;
  line-height: 1.7;
  color: #002A41;
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

.call-for-submissions {
  background: #002A41;
  color: white;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  max-width: 900px;
  text-align: center;
}

.call-for-submissions .deadline-box {
  font-size: 1.1rem;
  background: white;
  color: #002A41;
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 15px;
  font-weight: 500;
  margin-top: 1.5rem;
}

/* Responsive adjustments */
@media (max-width: 900px) {
  .hero { height: 60vh; min-height: 320px; }
  .hero-content h1 { font-size: 2rem; }
  #yt-player iframe { width: 200vh; } /* asegurar cobertura en tall viewports */
}
</style>


<!-- === ABOUT SECTION === -->
<section id="about" class="fade-in">
  <h2>💡 About the Event</h2>
  <t>
    The <strong>Durham HPC Days</strong> bring together researchers, developers, and practitioners
    to explore the frontiers of high-performance computing, data analysis, and scientific innovation.
  </t>
</section>




<!-- === HERO CON YOUTUBE EMBED === -->
<div class="hero">
  <div id="yt-player-wrap" aria-hidden="true">
    <div id="yt-player"></div>
  </div>

  <div class="hero-content">
    <h1>Durham HPC Days 2025 Video Recap</h1>
    <p>Take a look back at Durham HPC Days 2025 in this short recap featuring our keynote speakers</p>
    <a href="https://youtu.be/wPjtwACmaUg?si=E7VOWWcH5pda8ZSr" class="btn">View Video</a>
    <a href="https://durham.readthedocs.io/en/latest/hpcdays2025/index.html" class="btn">Visit last year's website</a>
  </div>
</div>

<div style="position: relative; z-index: 1;">
<section class="call-for-submissions fade-in">
  <h2>📢 Call for Submissions</h2>
  <p>
    We invite submissions for talks, workshops, and poster sessions at the
    <strong>Durham HPC Days 2026</strong>.
    This is an opportunity to share your work, inspire others, and shape the future of high-performance computing research.
  </p>
  <div class="deadline-box">
    🗓️ Submission Deadline: <strong>to be announced</strong>
  </div>
  <br><br>
  <a href="/Durham-HPC-Days/submissions" class="btn" style="background: #0055aa;">
    Submit Your Abstract
  </a><br> <br>
</section>


<!-- === HEADER IMAGE (si la necesitas puedes mantenerlo) === -->
<div class="header-image"></div>

<!-- === GALLERY SECTION === -->
<section id="gallery" class="fade-in">
  <h2>📸 Gallery</h2>
  <div class="image-grid">
    <img src="/Durham-HPC-Days/assets/images/Sessions.jpg" alt="Sessions">
    <img src="/Durham-HPC-Days/assets/images/food-truck.jpg" alt="Food truck">
    <img src="/Durham-HPC-Days/assets/images/social.png" alt="social">
    <img src="/Durham-HPC-Days/assets/images/stickers.jpg" alt="stickers">
  </div>
</section>

<!-- === PROGRAMME SECTION === -->
<section id="programme" class="fade-in">
  <h2>🗓️ Explore the Programme</h2>
  <t style="max-width: 700px; margin: 0 auto 2rem;">
    Discover the full schedule of keynotes, technical sessions, and social events for the upcoming conference.
    Check the programme to plan your participation and make the most of your experience at Durham HPC Days.
  </t><br>
  <a href="/Durham-HPC-Days/programme" class="btn">View Full Programme</a>
</section>


<script>
/* Fade-in animation on scroll */
(function() {
  function onScroll() {
    document.querySelectorAll('.fade-in').forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) el.classList.add('visible');
    });
  }
  document.addEventListener('scroll', onScroll);
  document.addEventListener('DOMContentLoaded', onScroll);
})();

/* --- YouTube IFrame API loader y player init --- */
(function loadYouTubeAPI(){
  if (window.YT && window.YT.Player) { initPlayer(); return; }
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/iframe_api";
  var firstScript = document.getElementsByTagName('script')[0];
  firstScript.parentNode.insertBefore(tag, firstScript);
})();

const YT_VIDEO_ID = "wPjtwACmaUg"; // cambia si necesitas otro video
let player;

function onYouTubeIframeAPIReady() { initPlayer(); } // llamada por la API si se carga

function initPlayer() {
  if (player) return;
  player = new YT.Player('yt-player', {
    videoId: YT_VIDEO_ID,
    playerVars: {
      autoplay: 1,
      controls: 0,
      modestbranding: 1,
      rel: 0,
      showinfo: 0,
      mute: 1,
      playsinline: 1,
      iv_load_policy: 3
    },
    events: {
      onReady: function(e) {
        e.target.mute();
        // buscamos a los 15s y reproducimos
        seekAndPlay(15);
      },
      onStateChange: function(e) {
        if (e.data === YT.PlayerState.ENDED) {
          seekAndPlay(15);
        }
      }
    }
  });
}

function seekAndPlay(sec) {
  if (!player || !player.seekTo) return;
  try {
    player.seekTo(sec, true);
    player.playVideo();
  } catch (err) {
    setTimeout(() => {
      try { player.seekTo(sec, true); player.playVideo(); } catch (e) {}
    }, 500);
  }
}
</script>
