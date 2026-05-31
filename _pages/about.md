---
layout: archive
title: "About"
permalink: /
author_profile: true
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
    margin-top: 0 !important;
    padding-top: 0 !important;
  }

  @media (min-width: 1024px) {
    .archive {
      width: calc(100% - 320px) !important;
      float: none !important;
      margin-left: 320px !important;
      margin-right: 0 !important;
      padding-left: 1rem !important;
      padding-right: 4rem !important;
    }
  }

  .home-archive {
    font-family: 'DM Sans', sans-serif;
  }

  .home-archive section {
    margin: 0 !important;
    padding: 0 !important;
  }

  .home-hero {
    padding: 0.8rem 0 0.4rem;
    margin: 0 0 0.6rem 0;
  }

  .home-hero h1 {
    font-family: 'Lora', serif;
    font-size: 2.7rem;
    font-weight: 400;
    color: #1a1a1a;
    margin: 0 0 0.55rem !important;
    line-height: 1.15;
  }

  .home-item {
    padding: 1rem 0;
  }

  .home-item:last-child {
    border-bottom: 1px solid #f0f0f0;
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

<div class="home-archive">
  <div class="home-item">
    <p class="home-text">
      I am a Fulbright Scholar and MA Candidate at the <a href="https://ijlinz.es">Juan Linz Institute</a> (IJL) at <a href="https://www.uc3m.es/Home">Carlos III University of Madrid</a> (UC3M), and an incoming PhD student in Sociology at <a href="https://as.nyu.edu/departments/sociology.html">New York University</a>. I received a BBA in International Business.
    </p>

    <p class="home-text">
      As an economic sociologist, I primarily study financial and labor markets in postindustrial economies. My work explores how expanding access to credit reshapes social and political life, from stock market participation to employee ownership schemes. I’m particularly interested in understanding how financial markets influence people’s sense of uncertainty and their stake—or “buy-in”—in the economy.
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