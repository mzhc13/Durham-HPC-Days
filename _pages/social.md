---
layout: splash
title: "Conference Social"
permalink: /social/
---

<style>
  /* ----- MAIN SECTION WITH FIXED BACKGROUND ----- */
  .social-bg {
    position: relative;
    background: url("/Durham-HPC-Days/assets/images/river-durham.jpeg") no-repeat center center fixed;
    background-size: cover;
    color: white;
    overflow: hidden;
  }

  /* Dark overlay to improve text contrast */
  .social-bg::before {
    content: "";
    position: absolute;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0, 0, 0, 0.70);
    z-index: 0;
  }

  /* Content on top of background */
  .social-content {
    position: relative;
    z-index: 1;
    padding: 4em 10%;
  }

  /* Typography */
  h1, h2 {
    text-align: center;
    color: #fff;
  }

  h1 {
    font-size: 3em;
    margin-top: 1em;
  }

  h2 {
    margin-top: 2.5em;
    color: #E3E8FF;
  }

  p, li {
    font-size: 1.1em;
  }

  ul {
    list-style-type: disc;
    margin-left: 2em;
  }

  .highlight {
    background: rgba(255,255,255,0.15);
    padding: 0.8em 1em;
    border-radius: 10px;
    margin: 1.2em 0;
  }

  a {
    color: #b3e6ff;
    text-decoration: none;
    border-bottom: 1px dotted #b3e6ff;
  }

  a:hover {
    color: #fff;
    border-bottom: 1px solid #fff;
  }

  .footer-note {
    text-align: center;
    font-size: 0.9em;
    opacity: 0.8;
    margin-top: 4em;
  }
</style>

<!-- ====== PAGE CONTENT ====== -->
<div class="social-bg">
  <div class="social-content">
    <h1>Conference Social Event</h1>
    <p style="text-align:center; font-size:1.2em; margin-top: -0.5em;">
      Join us for a day outdoors with colleagues and friends
    </p>

    <div class="highlight">
      <p><br>Join us for a day outdoors with colleagues and friends!
  This year’s <strong>conference social</strong> will include a group trip.
  Below you’ll find the provisional agenda, safety information, and details for additional participants.</p>
    </div>

    <h2>🗓️ Agenda</h2>
    <p><em>The agenda is yet to be confirmed by the bus company.</em></p>
    <ul>
      <li><strong>08:00, Departure</strong> from the Department of Computer Science. Participants may leave their luggage on the bus.</li>
      <li>There will likely be <strong>two return options</strong> — around lunchtime <strong>13:00</strong> and in the evening <strong>18:00</strong>.</li>
      <li>We will collect preferred return times upon departure, but participants are responsible for arriving at the pick-up points on time.</li>
    </ul>

    <h2>⚠️ Insurance and Risk</h2>
    <div class="highlight">
      <strong>Important:</strong> Hiking is a physically demanding activity and involves a degree of risk.  
      Participants join the trip at their own risk — organisers are not liable for personal injuries or accidents.
    </div>

    <ul>
      <li><strong>Emergency contact</strong> and relevant <strong>medical information</strong> will be collected and shared with paramedics if required.</li>
      <li>Please ensure you have suitable <strong>footwear</strong>, <strong>waterproof clothing</strong>, and bring sufficient <strong>water and snacks</strong>.</li>
    </ul>

    <h2>👥 Further Participants</h2>
    <p>We may be able to fill any empty seats on the bus with <strong>partners or friends</strong>.  
    If you would like to bring someone along, please <strong>contact the organisers in advance</strong> to check availability.</p>

    <h2>📩 Contact</h2>
    <p>For questions or further details, please contact:<br>
    <strong>Organisers:</strong> <a href="mailto:organisers@durham.ac.uk">organisers@durham.ac.uk</a></p>

    <div class="footer-note">
      © 2025 Durham University · Department of Computer Science
    </div>
  </div>
</div>

