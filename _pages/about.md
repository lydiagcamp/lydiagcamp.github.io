---
layout: archive
title: "About"
permalink: /
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .page__title { display: none; }
</style>

{% include base_path %}

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400;0,500;1,400&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet">

<style>
  .archive {
    width: 100% !important;
    float: none !important;
    margin-left: 0 !important;
    margin-right: 0 !important;
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  @media (min-width: 1024px) {
    .archive {
      padding-left: 3rem !important;
      padding-right: 8rem !important;
    }
  }

  .about-layout {
    display: flex;
    gap: 3rem;
    align-items: center;
    font-family: 'DM Sans', sans-serif;
  }

  .about-photo img {
    width: 260px;
    height: 260px;
    object-fit: cover;
    object-position: center top;
    display: block;
    flex-shrink: 0;
  }

  .about-content {
    flex: 1;
  }

  .home-text {
    font-size: 0.95rem;
    color: #555;
    margin: 1rem 0 !important;
    line-height: 1.75;
  }

  .home-text a,
  .home-text a:visited {
    color: #8b2032;
    text-decoration: underline;
    text-underline-offset: 3px;
    text-decoration-thickness: 1.1px;
  }

  .home-text a:hover {
    color: #6e1828;
  }
</style>

<div class="about-layout">
  <div class="about-photo">
    <img src="/images/profilezoom.jpeg" alt="Lydia Camp">
  </div>

  <div class="about-content">
    <p class="home-text">
      I am a Fulbright Scholar and MA Candidate at the <a href="https://ijlinz.es">Juan Linz Institute</a> (IJL) at <a href="https://www.uc3m.es/Home">Carlos III University of Madrid</a> (UC3M), and an incoming PhD student in Sociology at <a href="https://as.nyu.edu/departments/sociology.html">New York University</a>. I received a BBA in International Business.
    </p>

    <p class="home-text">
      As an economic sociologist, I primarily study financial and labor markets in postindustrial economies. My work explores how expanding access to credit reshapes social and political life, from stock market participation to employee ownership schemes. I'm particularly interested in understanding how financial markets influence people's sense of uncertainty and their stake—or "buy-in"—in the economy.
    </p>

    <p class="home-text home-social-row">
      <a href="/files/cv.pdf" class="cv-button">Download CV</a>
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}" class="social-icon-btn" aria-label="Email"><i class="fas fa-envelope"></i></a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" class="social-icon-btn" aria-label="GitHub" target="_blank"><i class="fab fa-github"></i></a>{% endif %}
      {% if site.author.linkedin %}<a href="https://linkedin.com/in/{{ site.author.linkedin }}" class="social-icon-btn" aria-label="LinkedIn" target="_blank"><i class="fab fa-linkedin"></i></a>{% endif %}
      <a href="https://bsky.app/profile/lydiacamp.bsky.social" class="social-icon-btn" aria-label="Bluesky" target="_blank"><svg viewBox="0 0 24 24" width="14" height="14" fill="currentColor"><path d="M12 10.8c-1.087-2.114-4.046-6.053-6.798-7.995C3.447 1.247 2.035.836 1.287.98c-.95.189-1.287 1.005-1.287 1.838 0 .96.32 3.793.533 4.98.68 3.72 3.147 4.95 5.44 4.698-.04.005-.08.01-.12.016-2.44.348-4.6 1.372-1.787 4.863C6.6 19.98 9.4 21.4 12 21.4s5.4-1.42 8.067-5.025c2.813-3.491.653-4.515-1.787-4.863-.04-.006-.08-.011-.12-.016 2.293.252 4.76-.978 5.44-4.698.213-1.187.533-4.02.533-4.98 0-.833-.337-1.649-1.287-1.838-.748-.144-2.16.267-3.915 1.825C17.046 4.747 14.087 8.686 12 10.8z"/></svg></a>
    </p>
  </div>
</div>
