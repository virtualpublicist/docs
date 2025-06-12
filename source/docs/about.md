---
title: About 
description: How to Use the Press Release Generator
extends: _layouts.documentation
section: content
---
<!-- Fonts & Styles -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<style>
  body {
    font-family: 'Inter', sans-serif;
    background-color: #001219;
    margin: 0;
    color: #000000
    padding: 0;
  }
  .section {
    padding: 80px 5%;
  }
  h1, h2 {
    color: #FFFFFF;
  }
  .headline {
    font-size: 3rem;
    font-weight: 700;
    color: #FFFFFF;
  }
  .subtext {
    font-size: 1.1rem;
    color: #CBD5E1;
    max-width: 800px;
    line-height: 1.6em;
  }
  .highlight {
    color: #3B82F6;
    font-weight: 600;
  }
  .stats {
    display: flex;
    justify-content: space-around;
    background-color: #0A0F1C;
    border-radius: 12px;
    padding: 50px 0;
    margin-top: 40px;
    text-align: center;
    flex-wrap: wrap;
    gap: 2em;
  }
  .stat-block h2 {
    font-size: 2.5rem;
    margin: 0;
    color: #3B82F6;
  }
  .cta {
    background: linear-gradient(90deg, #3B82F6, #1E3A8A);
    color: white;
    text-align: center;
    padding: 60px 20px;
    border-radius: 12px;
    margin-top: 60px;
  }
  .cta a {
    display: inline-block;
    margin-top: 20px;
    background-color: #001219;
    color: white;
    padding: 14px 30px;
    border-radius: 6px;
    text-decoration: none;
    font-weight: bold;
  }
  .partners {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 3em;
    flex-wrap: wrap;
    margin-top: 40px;
    opacity: 0.85;
  }
  .founders {
    display: flex;
    align-items: center;
    gap: 2em;
    flex-wrap: wrap;
    margin-top: 40px;
  }
  .founders img {
    max-width: 100%;
    border-radius: 10px;
  }
</style>

<!-- Hero Section -->
<section class="section" style="text-align:center;">
  <h1 class="headline">About Virtual Publicist</h1>
  <p class="subtext" style="margin-top: 20px;">
    Virtual Publicist is the <span class="highlight">future of music PR</span>. We give artists direct access to blogs, curators, and media opportunities — powered by AI and designed to scale with your journey.
  </p>
</section>

<!-- Mission Section -->
<section class="section" style="display: flex; gap: 3em; flex-wrap: wrap;">
  <div style="flex: 1; min-width: 280px;">
    <h2>We're making access global.</h2>
    <p class="subtext">
      Artists shouldn't need a manager or label to be seen and heard. Our mission is to democratize exposure and simplify PR for every artist, everywhere.
    </p>
  </div>
  <div style="flex: 1; min-width: 280px;">
    <h2>AI-powered. Artist-first.</h2>
    <p class="subtext">
      Our dashboard gives creators the tools they need to pitch smarter, connect faster, and build real visibility without gatekeepers.
    </p>
  </div>
</section>

<!-- Meet the Founders -->
<section class="section">
  <h2 style="text-align:center;">Meet the Founders</h2>
  <div class="founders">
    <img src="/assets/images/founders-photo.jpg" alt="Founders of Virtual Publicist" style="width: 45%;">
    <div style="flex: 1;">
      <p class="subtext">
        The duo behind Virtual Publicist has over 15 years of experience in music PR, artist management, and creative tech. They've worked with chart-topping musicians and world-class festivals — and now they’re putting that power into your hands.
      </p>
      <p class="subtext" style="font-style: italic;">
        "We built Virtual Publicist for the bedroom artist with superstar talent."
      </p>
    </div>
  </div>
</section>

<!-- Stats -->
<section class="stats">
  <div class="stat-block">
    <h2>10K+</h2>
    <p>Campaigns Launched</p>
  </div>
  <div class="stat-block">
    <h2>3K+</h2>
    <p>Verified Contacts</p>
  </div>
  <div class="stat-block">
    <h2>50+</h2>
    <p>Countries Reached</p>
  </div>
</section>

<!-- Partner Logos -->
<section class="section" style="text-align:center;">
  <h2>Our Partners & Media Network</h2>
  <div class="partners">
    <img src="/assets/images/sony-music.png" alt="Sony Music" height="40">
    <img src="/assets/images/universal-music.png" alt="Universal Music" height="40">
    <img src="/assets/images/warner-music.png" alt="Warner Music" height="40">
    <img src="/assets/images/rolling-stone.png" alt="Rolling Stone" height="40">
    <img src="/assets/images/billboard.png" alt="Billboard" height="40">
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <h2>Need Music PR? <br><em>Let’s start now.</em></h2>
  <a href="https://virtualpublicist.com/create-account">Create Your Free Profile</a>
</section>