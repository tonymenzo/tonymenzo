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

1. TOC
{:toc}

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

  .orchestral-anim {
    display: block;
    width: 100%;
    height: 100%;
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

  #markdown-toc strong {
    font-weight: normal;
  }

  #markdown-toc a:hover strong {
    text-decoration: underline;
  }

  .section-heading {
    border: 1px solid black;
    padding: 0.4em 0.75em;
    display: block;
    text-align: center;
  }

  .main-content .section-heading {
    margin-bottom: 1.5rem;
  }

  .project-roles {
    display: flex;
    gap: 0.3em;
    margin-top: 0.25em;
  }

  .project-role {
    padding: 0 0.4em;
    border: 1px solid rgba(90, 90, 90, 0.55);
    border-radius: 2px;
    font-size: 0.6em;
    font-weight: 600;
    letter-spacing: 0.04em;
    text-transform: uppercase;
    color: rgba(70, 70, 70, 1);
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

## **Agentic Infrastructure**
{: .fw-700 .section-heading}

<div class="project-container">

  <div class="project-block" style="--thumb-scale: 0.55;" onclick="window.location.href='https://github.com/tonymenzo/heptapod'">
    <img src="{{ './images/thumbnails/code/heptapod_logo.svg' | relative_url }}" alt="HEPTAPOD" style="transform: scale(0.7);">
    <div class="project-top-text special-text">HEPTAPOD</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        HEP Toolkit for Agentic Planning, Orchestration, and Deployment
        <!-- <div class="project-roles">
          <span class="project-role">author</span>
          <span class="project-role">maintainer</span>
        </div> -->
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2512.15867" onclick="event.stopPropagation()">2512.15867</a>,
        <a href="https://arxiv.org/abs/2603.26990" onclick="event.stopPropagation()">2603.26990</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 0.95;" onclick="window.location.href='https://github.com/tonymenzo/toolbench'">
    <img src="{{ './images/thumbnails/code/toolbench_llp_allsystems.svg' | relative_url }}" alt="toolbench">
    <div class="project-top-text special-text">toolbench</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Benchmarking Agentic Tools and Harnesses
        <!-- <div class="project-roles">
          <span class="project-role">author</span>
          <span class="project-role">maintainer</span>
        </div> -->
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2610.18454" onclick="event.stopPropagation()">2610.18454</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://github.com/tonymenzo/hepbench'">
    <img src="{{ './images/thumbnails/code/hepbench_forward_llp.svg' | relative_url }}" alt="hepbench">
    <div class="project-top-text special-text">HEPBench</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Agentic Benchmarks for High Energy Physics
        <!-- <div class="project-roles">
          <span class="project-role">author</span>
          <span class="project-role">maintainer</span>
        </div> -->
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2610.18454" onclick="event.stopPropagation()">2610.18454</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 0.95;" onclick="window.location.href='https://github.com/alexr314/toolbase'">
    <img src="{{ './images/thumbnails/code/toolbase_stack.svg' | relative_url }}" alt="toolbase">
    <div class="project-top-text special-text">toolbase</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Package Manager for Agent Toolkits
        <!-- <div class="project-roles">
          <span class="project-role">co-author</span>
          <span class="project-role">maintainer</span>
        </div> -->
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2609.00107" onclick="event.stopPropagation()">2609.00107</a>,
        <a href="https://arxiv.org/abs/2610.18454" onclick="event.stopPropagation()">2610.18454</a>
      </div>
    </div>
  </div>

  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://github.com/orchestralAI/orchestral-ai'">
    <canvas class="orchestral-anim" aria-label="Orchestral logo animation"></canvas>
    <div class="project-top-text special-text">Orchestral</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        Provider-Agnostic Agent Orchestration
        <!-- <div class="project-roles">
          <span class="project-role">contributor</span>
          <span class="project-role">maintainer</span>
        </div> -->
      </div>
      <div class="project-subtext-strip">
        Based on:
        <a href="https://arxiv.org/abs/2601.02577" onclick="event.stopPropagation()">2601.02577</a>
      </div>
    </div>
  </div>
</div>

<!--- Orchestral logo animation, adapted from orchestral-ai.com --->
<script>
(function () {
  var canvas = document.querySelector('.orchestral-anim');
  if (!canvas) return;
  var ctx = canvas.getContext('2d');
  var block = canvas.closest('.project-block');
  var reduceMotion = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  var phase = 0, speed = 1, targetSpeed = 1;

  function resize() {
    var dpr = window.devicePixelRatio || 1;
    canvas.width = canvas.clientWidth * dpr;
    canvas.height = canvas.clientHeight * dpr;
  }

  function draw() {
    var w = canvas.width, h = canvas.height;
    var r = Math.min(w, h) / 3.4, cy = h / 2;
    ctx.clearRect(0, 0, w, h);
    ctx.strokeStyle = 'rgba(10, 34, 78, 0.85)';
    ctx.lineWidth = Math.max(1.5, r / 60);
    [3, 4, 5, 6, 7, 8, 9].forEach(function (n) {
      ctx.beginPath();
      for (var a = 0; a <= 200; a++) {
        var t = a / 200 * 2 * Math.PI;
        var rho = 1 + 0.1 * Math.cos(n * t + phase);
        var x = w / 2 + rho * Math.cos(t + phase / 6) * r;
        var y = cy + rho * Math.sin(t + phase / 6) * r;
        a === 0 ? ctx.moveTo(x, y) : ctx.lineTo(x, y);
      }
      ctx.closePath();
      ctx.stroke();
    });
  }

  function tick() {
    speed += 0.05 * (targetSpeed - speed);
    phase = (phase + 12 * Math.PI / 600 * speed) % (12 * Math.PI);
    draw();
    requestAnimationFrame(tick);
  }

  block.addEventListener('mouseenter', function () { targetSpeed = 2; });
  block.addEventListener('mouseleave', function () { targetSpeed = 1; });
  window.addEventListener('resize', function () { resize(); draw(); });
  resize();
  reduceMotion ? draw() : tick();
})();
</script>

## **Phenomenology & Machine Learning**
{: .fw-700 .section-heading}

<div class="project-container">
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

## **Tutorials**
{: .fw-700 .section-heading}

Contributed tutorials on Monte Carlo event generation.

<div class="project-container">
  <div class="project-block" style="--thumb-scale: 1;" onclick="window.location.href='https://gitlab.com/mcgen-ct/tutorials'">
    <img src="{{ './images/thumbnails/code/fakelogo.png' | relative_url }}" alt="MCgen">
    <div class="project-top-text special-text">MCgen</div>
    <div class="project-overlay">
      <div class="project-text-strip">
        MCgen - Monte Carlo Event Generation Tutorials
        <!-- <div class="project-roles">
          <span class="project-role">contributor</span>
        </div> -->
      </div>
    </div>
  </div>
</div>