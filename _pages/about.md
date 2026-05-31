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
      <a href="/files/websiteCV.pdf" class="cv-button">Download CV</a>
      {% if site.author.email %}<a href="mailto:{{ site.author.email }}" class="social-icon-btn" aria-label="Email"><i class="fas fa-envelope"></i></a>{% endif %}
      {% if site.author.github %}<a href="https://github.com/{{ site.author.github }}" class="social-icon-btn" aria-label="GitHub" target="_blank"><i class="fab fa-github"></i></a>{% endif %}
      {% if site.author.linkedin %}<a href="https://linkedin.com/in/{{ site.author.linkedin }}" class="social-icon-btn" aria-label="LinkedIn" target="_blank"><i class="fab fa-linkedin"></i></a>{% endif %}
      {% if site.author.twitter %}<a href="https://twitter.com/{{ site.author.twitter }}" class="social-icon-btn" aria-label="X" target="_blank"><i class="fab fa-x-twitter"></i></a>{% endif %}
    </p>
  </div>
</div>
