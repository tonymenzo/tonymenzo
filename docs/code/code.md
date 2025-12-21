---
layout: default
title: Code
nav_order: 3
has_children: true
permalink: docs/code
mathjax: true
---
# **Code**
{: .fw-700}

A number of my publications are accompanied by open-source software. Relevant repositories are linked below.

<style>
  .project-container {
    display: grid;
    grid-template-columns: 1fr;
    gap: 2rem 1rem;
    width: 98%;
  }

  .project-block {
    position: relative;
    overflow: hidden;
    width: 100%;
    aspect-ratio: 3.236 / 2.2;
    max-width: 350px;
    background-color: #e0e0e0;
    display: block;
    border: 1px solid black;
    text-decoration: none;
    color: inherit;
    cursor: pointer;
  }

  .project-block img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    object-position: center;
    transform: scale(var(--thumb-scale, 1));
    transform-origin: center;
    display: block;
    image-rendering: crisp-edges;
    image-rendering: -webkit-optimize-contrast;
  }

  .project-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%; height: 100%;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
    padding: 3px 3px 3px 3px;
    background-color: rgba(250, 250, 250, 0.6);
  }

  .project-text-strip {
    width: 100%;
    margin-top: 0;
    background: rgba(255, 255, 255, 0.4);
    backdrop-filter: blur(3px);
    -webkit-backdrop-filter: blur(3px);
    color: rgba(49, 49, 49, 1);
    font-size: 0.9em;
    font-weight: 900;
    padding: 0.5em 0.75em;
    text-align: left;
    border: 1px solid #ccc;
  }

  .project-subtext-strip {
    max-width: 70%;
    margin-top: 0.3em;
    background: rgba(255, 255, 255, 0.85);
    backdrop-filter: blur(4px);
    -webkit-backdrop-filter: blur(4px);
    color: rgba(40, 40, 40, 1);
    font-size: 0.7em;
    font-weight: 600;
    padding: 0.4em 0.75em;
    text-align: left;
    border: 1px solid rgba(200, 200, 200, 0.8);
    align-self: flex-start;
  }

  .project-subtext-strip a {
    color: rgba(5, 95, 168, 1);
    text-decoration: none;
    font-weight: 700;
  }

  .project-subtext-strip a:hover {
    text-decoration: underline;
  }

  .project-top-text {
    position: absolute;
    bottom: 0px;
    right: 10px;
    color: rgba(202, 19, 19, 1);
    font-weight: bold;
    padding: 0em 0em;
    z-index: 2;
  }

  @media (min-width: 600px) {
    .project-container {
      grid-template-columns: repeat(2, 1fr);
    }
  }
</style>

<!--- Import external font --->
<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@900&display=swap" rel="stylesheet">
<style>
.special-text {
  font-family: "Orbitron", normal;
  font-size: 1.1em;
  font-weight: 900;
  color: #111111ff;
  margin: 0.1em 0.1em;
}
</style>

<div class="project-container">

  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://github.com/tonymenzo/heptapod'">
    <img src="{{ './images/thumbnails/code/heptapod_diagram_focused.svg' | relative_url }}" alt="RSA">
    <div class="project-top-text special-text">HEPTAPOD</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        HEP Toolkit for Agentic Planning, Orchestration, and Deployment
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2512.15867" onclick="event.stopPropagation()">2512.15867</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 0.9;" onclick="window.location.href='https://gitlab.com/uchep/mlhad'">
    <img src="{{ './images/thumbnails/code/MLHAD_logo.svg' | relative_url }}" alt="MLHAD">
    <div class="project-top-text special-text">MLHAD</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Machine Learning for Hadronization
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2203.04983" onclick="event.stopPropagation()">2203.04983</a>,
        <a href="https://arxiv.org/abs/2311.09296" onclick="event.stopPropagation()">2311.09296</a>,
        <a href="https://arxiv.org/abs/2410.06342" onclick="event.stopPropagation()">2410.06342</a>,
        <a href="https://arxiv.org/abs/2411.02194" onclick="event.stopPropagation()">2411.02194</a>,
        <a href="https://arxiv.org/abs/2503.05667" onclick="event.stopPropagation()">2503.05667</a>,
        <a href="https://arxiv.org/abs/2505.00142" onclick="event.stopPropagation()">2505.00142</a>,
        <a href="https://arxiv.org/abs/2509.03592"
        onclick="event.stopPropagation()">2509.03592</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://github.com/tonymenzo/RSA'">
    <img src="{{ './images/thumbnails/code/multiplicity.pdf' | relative_url }}" alt="RSA">
    <div class="project-top-text special-text">RSA</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Rejection Sampling with Autodifferentiation
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2411.02194" onclick="event.stopPropagation()">2411.02194</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 1.1;" onclick="window.location.href='https://github.com/adamdddave/emd4cpv'">
    <img src="{{ './images/thumbnails/code/gaussian_flow_q_0.1.png' | relative_url }}" alt="EMD4CPV">
    <div class="project-top-text special-text">EMD4CPV</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Earth Mover's Distance for CP Violation
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2301.13211" onclick="event.stopPropagation()">2301.13211</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://github.com/Berkeley-Electroweak-Physics/MuonBridge'">
    <img src="{{ './images/thumbnails/code/WET_NRET_matching.svg' | relative_url }}" alt="MuonBridge">
    <div class="project-top-text special-text">MuonBridge</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        EFT tower for &mu; &rarr; e conversion
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2406.13818" onclick="event.stopPropagation()">2406.13818</a>
      </div>
    </div>
  </div>
</div>

# **Tutorials**
{: .fw-700}

I have also contributed to a set of nice tutorials related to Monte-Carlo event generation. The public repository is linked below.

<div class="project-container">
  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://gitlab.com/mcgen-ct/tutorials'">
    <img src="{{ './images/thumbnails/code/fakelogo.png' | relative_url }}" alt="MCgen">
    <div class="project-top-text special-text">MCgen</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        MCgen - Monte Carlo Event Generation Tutorials
      </div>
    </div>
  </div>
</div>