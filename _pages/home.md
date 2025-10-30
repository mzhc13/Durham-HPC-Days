---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/background.png


feature_row:
  - image_path: /assets/images/logo.png
    alt: "About"
    title: "About SHAREing"
    excerpt: "More about SHAREing, its vision and the people behind the project"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Find out more"
  - image_path: /assets/images/home-assessment.png
    alt: "Assessments"
    title: "Performance and machine assessments"
    excerpt: "SHAREing provides performance and machine assessments to the wider UK computational science community."
    url: "/assessment/"
    btn_class: "btn--primary"
    btn_label: "Find out more"
  - image_path: /assets/images/home-training.png
    alt: "Training"
    title: "Training"
    excerpt: "SHAREing collects information around acceleate-focused training, but also organises and creates its own training material."
    url: "/training/"
    btn_class: "btn--primary"
    btn_label: "Find out more"
  - image_path: /assets/images/home-events.png
    alt: "Events schedule"
    title: "SHAREing events"
    excerpt: "Many of SHAREing's core outputs (training, assessments, scoping exercises, landscape analyses, ...) are delivered through a wide range of events."
    url: "/events/"
    btn_class: "btn--primary"
    btn_label: "View schedule"
  - image_path: /assets/images/home-resources.png
    alt: "resources"
    title: "SHAREing resources"
    excerpt: "SHAREing's outcomes are available freely to the UK community."
    url: "/resources/"
    btn_class: "btn--primary"
    btn_label: "Access these"
  - image_path: /assets/images/home-network.png
    alt: "network"
    title: "Network"
    excerpt: "SHAREing is part of a wider ensemble of Digital Research Infrastructure (DRI) projects and itself embedded into a network of partners."
    url: "/network/"
    btn_class: "btn--primary"
    btn_label: "Find out more"
---

# News
<div class="video-banner">
  <video autoplay muted loop playsinline>
    <source src="/assets/video.mp4" type="video/mp4">
  </video>

  <div class="video-overlay">
    <h2>Welcome to SHAREing</h2>
    <p>Empowering performance and innovation across the UK HPC community</p>
  </div>
</div>

<style>
.video-banner {
  position: relative;
  width: 100vw;
  height: 70vh; /* adjust the height of the banner */
  overflow: hidden;
  margin: 0;
  padding: 0;
  border-radius: 0;
}

.video-banner video {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  height: 100%;
  object-fit: cover;      /* fill container with cropping */
  object-position: 50% 50%; /* control visible area */
  transform: translate(-50%, -50%);
  z-index: -1;
}

.video-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: white;
  background: rgba(0, 0, 0, 0.25); /* subtle overlay for readability */
  backdrop-filter: blur(2px);
}

.video-overlay h2 {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 0.5rem;
}

.video-overlay p {
  font-size: 1.2rem;
  max-width: 700px;
}

</style>
